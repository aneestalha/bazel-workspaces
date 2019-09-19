cc_library(
    name = "base",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_base_libbase",
        "-labsl_base_libdynamic_annotations",
        "-labsl_base_libexception_safety_testing",
        "-labsl_base_libmalloc_internal",
        "-labsl_base_libspinlock_wait",
        "-labsl_base_libthrow_delegate",
        "-lgtest",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
