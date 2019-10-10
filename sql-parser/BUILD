cc_library(
    name = "sqlparser",
    hdrs = glob(["thirdparty_build/include/hsql/**/*.h"]),
    copts = ["-I/usr/include/hsql"],
    linkopts = ["-lsqlparser"],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
