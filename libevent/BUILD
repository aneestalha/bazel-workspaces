cc_library(
    name = "libevent",
    hdrs = glob([
        "thirdparty_build/include/evdns.h",
        "thirdparty_build/include/event.h",
        "thirdparty_build/include/evhttp.h",
        "thirdparty_build/include/evrpc.h",
        "thirdparty_build/include/evutil.h",
        "thirdparty_build/include/event2/**/*.h",
    ]),
    copts = ["-I/usr/include", "-I/usr/include/event2"],
    linkopts = [
        "-levent",
        "-levent_core",
        "-levent_extra",
        "-levent_pthreads",
        "-levent_openssl",
    ],
    visibility = ["//visibility:public"],
    linkstatic = False,
)
