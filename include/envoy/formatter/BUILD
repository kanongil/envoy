licenses(["notice"])  # Apache 2

load(
    "//bazel:envoy_build_system.bzl",
    "envoy_cc_library",
    "envoy_package",
)

envoy_package()

envoy_cc_library(
    name = "substitution_formatter_interface",
    hdrs = ["substitution_formatter.h"],
    deps = [
        "//include/envoy/config:typed_config_interface",
        "//include/envoy/http:header_map_interface",
        "//include/envoy/stream_info:stream_info_interface",
    ],
)
