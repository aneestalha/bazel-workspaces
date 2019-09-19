cc_library(
    name = "node_hash_set",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_synchronization_libgraphcycles_internal",
        "-labsl_synchronization_libper_thread_sem_test_common",
        "-labsl_synchronization_libsynchronization",
    ],
    deps = [
        "//absl/debugging:stacktrace",
        "//absl/debugging:symbolize",
        "//absl/time",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
