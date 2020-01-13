cc_library(
    name = "crypto",
    hdrs = glob(["thirdparty_build/include/openssl/**/*.h"]),
    copts = ["-I/usr/include/openssl"],
    linkopts = [
        "-lcrypto",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "ssl",
    hdrs = glob(["thirdparty_build/include/openssl/**/*.h"]),
    copts = ["-I/usr/include/openssl"],
    linkopts = [
        "-lssl",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
    deps = [
        ":crypto",
    ],
)
