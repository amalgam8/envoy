licenses(["notice"])  # Apache 2

load(
    "//bazel:envoy_build_system.bzl",
    "envoy_cc_test",
    "envoy_package",
)

envoy_package()

envoy_cc_test(
    name = "utility_test",
    srcs = ["utility_test.cc"],
    external_deps = ["envoy_bootstrap"],
    deps = [
        "//source/common/protobuf:utility_lib",
        "//test/test_common:environment_lib",
        "//test/test_common:utility_lib",
    ],
)
