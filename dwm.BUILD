package(default_visibility = ["//visibility:public"])

cc_library(
    name = "util",
    srcs = ["dwm-master/util.c"],
    hdrs = ["dwm-master/util.h"],
    copts = [
	"-std=c99",
        "-pedantic",
        "-Wall",
        "-Wno-deprecated-declarations",
        "-Os",
    ],
    defines = [
        "_DEFAULT_SOURCE",
        "_BSD_SOURCE",
        "_POSIX_C_SOURCE=200809L",
        "XINERAMA",
        'VERSION=\\"6.2\\"',
    ],
)

cc_library(
    name = "drw",
    srcs = ["dwm-master/drw.c"],
    hdrs = ["dwm-master/drw.h"],
    deps = [":util"],
    copts = [
	"-std=c99",
        "-pedantic",
        "-Wall",
        "-Wno-deprecated-declarations",
        "-Os",
    ],
    defines = [
        "_DEFAULT_SOURCE",
        "_BSD_SOURCE",
        "_POSIX_C_SOURCE=200809L",
        "XINERAMA",
        'VERSION=\\"6.2\\"',
    ],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
)
