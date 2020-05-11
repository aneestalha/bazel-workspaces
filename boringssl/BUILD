cc_library(
    name = "crypto",
    hdrs = glob(["thirdparty_build/include/boringssl/**/*.h"]),
    copts = ["-I/usr/include/boringssl"],
    linkopts = [
        "-lboringssl_crypto",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "ssl",
    hdrs = glob(["thirdparty_build/include/boringssl/**/*.h"]),
    copts = ["-I/usr/include/boringssl"],
    linkopts = [
        "-lboringssl_ssl",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
    deps = [
        ":crypto",
    ],
)
