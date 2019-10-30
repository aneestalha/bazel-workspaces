cc_library(
    name = "grpc",
    hdrs = glob(["thirdparty_build/include/gprc/**/*.h"]),
    copts = ["-I/usr/include/grpc"],
    linkopts = [
        "-lgrpc",
        "-lgrpc_cronet",
        "-lgrpc_unsecure",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)

cc_library(
    name = "grpc++",
    hdrs = glob(["thirdparty_build/include/gprc++/**/*.h"]),
    copts = ["-I/usr/include/gprc++"],
    linkopts = [
        "-lgrpc++",
        "-lgrpc++_error_details",
        "-lgrpc++_reflection",
        "-lgprc++_unsecure",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
