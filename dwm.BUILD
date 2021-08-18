package(default_visibility = ["//visibility:public"])

filegroup(
    name = "srcs",
    srcs = glob(["**/*.c"]),
)

filegroup(
    name = "hdrs",
    srcs = glob(["**/*.h"]),
)

cc_library(
    name = "util",
    srcs = ["dwm-master/util.c"],
    hdrs = ["dwm-master/util.h"],
)

cc_library(
    name = "drw",
    srcs = ["dwm-master/drw.c"],
    hdrs = ["dwm-master/drw.h"],
)

filegroup(
    name = "dwm",
    srcs = ["dwm-master/dwm.c"],
)
