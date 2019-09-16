cc_library(
    name = "spdlog",
    hdrs = glob(["thirdparty_build/include/spdlog/**/*.h"]),
    copts = ["-I/usr/include/spdlog"],
    linkopts = [],
    visibility = ["//visibility:public"],
    linkstatic=False,
    deps = ["@com_github_fmtlib_fmt//:fmtlib"],
    defines = ["SPDLOG_FMT_EXTERNAL"],
)
