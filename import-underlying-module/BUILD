package(default_visibility = ["//visibility:public"])

load("@bazel_tools//tools/build_defs/apple:swift.bzl", "swift_library")

swift_library(
    name = "Foo",
    module_name = "Foo",
    srcs = glob(["*.swift"]),
#    copts = ['-import-underlying-module']
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
    visibility = ["//examples:__pkg__"],
)