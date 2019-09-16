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

Bazel allows to override repositories, so this project

## How to use this project?

```
--override_repository="repository_name=/location_of_this_git_repo/repository"
```
