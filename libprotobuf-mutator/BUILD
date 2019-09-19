cc_library(
    name = "libprotobuf_mutator",
    hdrs = glob(["thirdparty_build/include/libprotobuf-mutator"]),
    copts = ["-I/usr/include/libprotobuf-mutator"],
    linkopts = ["-lprotobuf-mutator", "-lprotobuf-mutator-libfuzzer"],
    visibility = ["//visibility:public"],
    linkstatic=False,
)
