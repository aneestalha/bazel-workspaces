cc_library(
    name = "any",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_types_libbad_any_cast_impl",
        "-labsl_types_libbad_optional_access",
        "-labsl_types_libbad_variant_access",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "optional",
    hdrs = glob(["thirdparty_build/include/absl/**/*.h"]),
    copts = ["-I/usr/include/absl"],
    linkopts = [
        "-labsl_types_libbad_any_cast_impl",
        "-labsl_types_libbad_optional_access",
        "-labsl_types_libbad_variant_access",
        "-labsl_types_liboptional",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
