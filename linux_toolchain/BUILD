load("@rules_cc//cc:defs.bzl", "cc_binary")
load("@com_github_bazelbuild_buildtools//buildifier:def.bzl", "buildifier")

buildifier(
    name = "buildifier",
    lint_mode = "warn",
    mode = "check",
    verbose = True,
)

cc_binary(
    name = "hello_world",
    srcs = ["hello_world.cpp"],
)
