cc_library(
    name = "strings",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_strings_libinternal",
        "-labsl_strings_libstrings",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "str_format",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_strings_libinternal",
        "-labsl_strings_libstrings",
        "-labsl_strings_libstr_format_internal",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
