cc_library(
    name = "re2",
    hdrs = glob(["thirdparty_build/include/re2/**/*.h"]),
    copts = ["-I/usr/include/re2"],
    linkopts = [
        "-lre2",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
