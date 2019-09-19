cc_library(
    name = "gperftools",
    hdrs = glob(["thirdparty_build/include/gperftools/**/*.h"]),
    copts = [],
    linkopts = ["-ltcmalloc", "-lprofiler"],
    visibility = ["//visibility:public"],
    linkstatic=False,
)
