licenses(["notice"])  # Zlib license, which is BSD/MIT-like

cc_library(
    name = "zlib",
    hdrs = glob([
        "thirdparty_build/include/zconf.h",
        "thirdparty_build/include/zlib.h",
    ]),
    copts = [],
    linkopts = ["-lz"],
    visibility = ["//visibility:public"],
    linkstatic=False,
)
