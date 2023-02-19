load("@rules_cc//cc:defs.bzl", "cc_test")
cc_test(
    name = "test",
    data = ["@my_largefile//:largefile"],
    srcs = glob([
        "*.cpp",
        "*.hpp",
    ]),
)