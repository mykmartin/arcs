load(
    "//third_party/java/arcs/build_defs:build_defs.bzl",
    "arcs_kt_jvm_test_suite",
)

licenses(["notice"])

package(default_visibility = ["//java/arcs:allowed-packages"])

arcs_kt_jvm_test_suite(
    name = "analysis",
    data = [
        "//java/arcs/core/data/testdata:examples",
        "//javatests/arcs/core/analysis/testdata:example_manifest_protos",
    ],
    package = "arcs.core.analysis",
    deps = [
        "//java/arcs/core/analysis",
        "//java/arcs/core/data",
        "//java/arcs/core/data:schema_fields",
        "//java/arcs/core/data/expression",
        "//java/arcs/core/data/proto",
        "//java/arcs/core/data/proto:manifest_java_proto_lite",
        "//java/arcs/core/data/proto:policy_java_proto_lite",
        "//java/arcs/core/policy",
        "//java/arcs/core/policy/proto",
        "//java/arcs/core/testutil/protoloader",
        "//java/arcs/core/util",
        "//java/arcs/repoutils",
        "//third_party/java/junit:junit-android",
        "//third_party/java/truth:truth-android",
        "//third_party/kotlin/kotlin:kotlin_test",
    ],
)
