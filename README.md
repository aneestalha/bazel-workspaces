# bazel-workspaces
Bazel workspaces for libraries packaged in openSUSE which allow to link those
libraries dynamically to software build by Bazel.

## Motivation
There is a difference in how software is build in Linux distributions and in
projects using Bazel.

The most of software built by Bazel usually bundles libraries. The usual way
is to download tarballs or git repositories and them build them as static
libraries. That approach is good for developers who are focused only on that
one particular project.

However, that approach doesn't work so well for Linux distributions. In distros
like openSUSE we need to ensure that updates or security fixes for the
particular are applied only once to have the effect on all packages and the
whole operating system. That's why globally available libraries and dynamic
linking is the best approach for us.

Bazel allows to override repositories, so this project uses that possibility to
provide custom repositories which allow to link libraries dynamically and use
`*-devel` packages in openSUSE as build dependencies.

## How to use this project?

```
--override_repository="repository_name=/location_of_this_git_repo/repository"
```

Or if you installed `bazel-workspaces` package in openSUSE:

```
--override_repository="repository_name=/usr/share/bazel-workspaces/repository"
```

Or in rpmspec:

```
--override_repository="repository_name=%{_datadir}/bazel-workspaces/repository"
```

Let's assume that your Bazel project depends on gperftools. After installing the
`bazel-workspaces` package, build your project like:

```
bazel build \
    --override_repository="com_github_gperftools_gperftools=/usr/share/bazel-workspaces/gperftools" \
    //...
```
