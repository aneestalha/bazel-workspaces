cc_library(
    name = "fmtlib",
    hdrs = glob(["thirdparty_build/include/fmt/**/*.h"]),
    copts = ["-I/usr/include/fmt"],
    visibility = ["//visibility:public"],
    linkstatic=False,
    linkopts = ["-lfmt"],
    defines = ["FMT_HEADER_ONLY"],
)
