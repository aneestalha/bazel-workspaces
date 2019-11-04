cc_library(
    name = "upb",
    hdrs = glob(["thirdparty_build/include/upb/**/*.h"]),
    copts = ["-I/usr/include/upb"],
    linkopts = [
        "-ldescriptor_upbproto",
        "-lupb",
        "-lupb_handlers",
        "-lupb_json",
        "-lupb_legacy_msg_reflection",
        "-lupb_pb",
        "-lupb_reflection",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
