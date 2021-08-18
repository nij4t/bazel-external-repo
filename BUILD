cc_binary(
    name = "main",
    deps = [
        "@dwm//:util",
        "@dwm//:drw",
        "@dwm//:dwm",
    ],
    linkopts = [
        '-L/usr/X11R6/lib',
        '-lX11',
        '-lXinerama',
        '-lfontconfig',
        '-lXft',
    ],
)

