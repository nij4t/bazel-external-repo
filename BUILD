cc_binary(
    name = "main",
    srcs = [":dwm"],
    deps = [
        "@dwm//:util",
        "@dwm//:drw",
    ],
    linkopts = [
        '-L/usr/X11R6/lib',
        '-lX11',
        '-lXinerama',
        '-lfontconfig',
        '-lXft',
    ],
)

cc_library(
    name = "dwm",
    srcs = [
        "@dwm//:dwm-master/dwm.c",
    ],
    hdrs = [
        "@dwm//:dwm-master/drw.h",
        "@dwm//:dwm-master/util.h",
        ":config.h",
    ],
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

