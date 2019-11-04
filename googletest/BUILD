cc_library(
    name = "googletest_main",
    hdrs = glob([
        "thirdparty_build/include/gmock/**/*.h",
        "thirdparty_build/include/gtest/**/*.h",
    ]),
    copts = [
        "-I/usr/include/gmock",
        "-I/usr/include/gtest",
    ],
    linkopts = [
        "-lgmock",
        "-lgmock_main",
        "-lgtest",
        "-lgtest_main",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "gtest",
    hdrs = glob(["thirdparty_build/include/gtest/**/*.h"]),
    copts = ["-I/usr/include/gtest"],
    linkopts = [
        "-lgtest",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "gtest_main",
    hdrs = glob(["thirdparty_build/include/gtest/**/*.h"]),
    copts = ["-I/usr/include/gtest"],
    linkopts = [
        "-lgtest_main",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "gmock",
    hdrs = glob(["thirdparty_build/include/gmock/**/*.h"]),
    copts = ["-I/usr/include/gmock"],
    linkopts = [
        "-lgmock",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "gmock_main",
    hdrs = glob(["thirdparty_build/include/gmock/**/*.h"]),
    copts = ["-I/usr/include/gmock"],
    linkopts = [
        "-lgmock_main",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
