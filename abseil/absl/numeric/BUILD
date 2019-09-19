cc_library(
    name = "int128",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_numeric_libint128",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
