package(default_visibility = ["//visibility:public"])

cc_library(
    name = "util",
    srcs = ["dwm-master/util.c"],
    hdrs = ["dwm-master/util.h"],
    copts = [
	'-std=c99',
        '-pedantic',
        '-Wall',
        '-Wno-deprecated-declarations',
        '-Os',
        '-D_DEFAULT_SOURCE',
        '-D_BSD_SOURCE',
        '-D_POSIX_C_SOURCE=200809L',
        '-DVERSION="6.2"',
        '-DXINERAMA'
    ],
)

cc_library(
    name = "drw",
    srcs = ["dwm-master/drw.c"],
    hdrs = ["dwm-master/drw.h"],
    deps = [":util"],
    copts = [
	'-std=c99',
        '-pedantic',
        '-Wall',
        '-Wno-deprecated-declarations',
        '-Os',
        '-D_DEFAULT_SOURCE',
        '-D_BSD_SOURCE',
        '-D_POSIX_C_SOURCE=200809L',
        '-DVERSION="6.2"',
        '-DXINERAMA',
    ],
)

cc_library(
    name = "dwm",
    srcs = [
        "dwm-master/dwm.c",
        "dwm-master/fibonacci.c",
    ],
    hdrs = [
        "dwm-master/drw.h",
        "dwm-master/util.h",
        "dwm-master/config.h",
    ],
    copts = [
	'-std=c99',
        '-pedantic',
        '-Wall',
        '-Wno-deprecated-declarations',
        '-Os',
        '-D_DEFAULT_SOURCE',
        '-D_BSD_SOURCE',
        '-D_POSIX_C_SOURCE=200809L',
        '-DVERSION="6.2"',
        '-DXINERAMA',
    ],
)

