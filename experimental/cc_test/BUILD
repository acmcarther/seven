cc_library(
    name = "demo_dep",
    srcs = [
        "demo_dep.cc",
    ],
    hdrs = [
        "demo_dep.h",
    ],
)

cc_binary(
    name = "demo",
    srcs = [
        "demo.cc",
    ],
    deps = [
        ":demo_dep",
    ],
)
