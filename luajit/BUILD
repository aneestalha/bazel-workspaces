cc_library(
    name = "luajit",
    hdrs = glob(["thirdparty_build/include/luajit-5_1-2.1/**/*.h"]),
    copts = ["-I/usr/include/luajit-5_1-2.1"],
    linkopts = ["-lluajit-5.1"],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
