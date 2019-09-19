cc_library(
    name = "hash",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_hash_libcity",
        "-labsl_hash_libhash",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "hash_testing",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_hash_libcity",
        "-labsl_hash_libhash",
        "-lgtest",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
