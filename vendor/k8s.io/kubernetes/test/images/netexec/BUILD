package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
)

go_binary(
    name = "netexec",
    srcs = ["netexec.go"],
    tags = ["automanaged"],
    deps = ["//pkg/util/net:go_default_library"],
)
