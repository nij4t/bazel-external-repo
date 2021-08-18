package(default_visibility = ["//visibility:public"])

cc_library(
    name = "util",
    srcs = ["dwm-master/util.c"],
    hdrs = ["dwm-master/util.h"],
)

cc_library(
    name = "drw",
    srcs = ["dwm-master/drw.c"],
    hdrs = ["dwm-master/drw.h"],
    deps = [":util"],
)

filegroup(
    name = "dwm",
    srcs = [
        "dwm-master/dwm.c",
        "dwm-master/config.h",
        "dwm-master/fibonacci.c",
    ],
)
