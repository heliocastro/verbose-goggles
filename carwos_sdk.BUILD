package(default_visibility = ['//visibility:public'])

filegroup(
    name = "all",
    srcs = glob(
        ["**/*"],
        exclude = [
            "lib/modules/**",
            "lib/firmware/**",
            "lib64/tcl/**",
            "lib64/gconv/**",
            "var/**",
            "usr/share/**",
        ],
    ),
    visibility = ["@//toolchain:__pkg__"],
)
