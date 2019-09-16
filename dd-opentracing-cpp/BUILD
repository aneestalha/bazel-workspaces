licenses(["notice"])  # Apache 2.0

cc_library(
    name = "dd_opentracing_cpp",
    hdrs = glob(["thirdparty_build/include/datadog/**/*.h"]),
    copts = ["-I/usr/include/datadog"],
    linkopts = ["-ldd_opentracing"],
    visibility = ["//visibility:public"],
    linkstatic=False,
)
