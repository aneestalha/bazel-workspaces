cc_library(
    name = "core",
    hdrs = glob(["thirdparty_build/include/prometheus/**/*.h"]),
    copts = ["-I/usr/include/prometheus"],
    linkopts = [
        "-lprometheus-cpp-core",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "pull",
    hdrs = glob(["thirdparty_build/include/prometheus/**/*.h"]),
    copts = ["-I/usr/include/prometheus"],
    linkopts = [
        "-lprometheus-cpp-pull",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "push",
    hdrs = glob(["thirdparty_build/include/prometheus/**/*.h"]),
    copts = ["-I/usr/include/prometheus"],
    linkopts = [
        "-lprometheus-cpp-push",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
