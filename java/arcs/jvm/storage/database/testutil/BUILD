load("//third_party/java/arcs/build_defs:build_defs.bzl", "arcs_kt_jvm_library")

licenses(["notice"])

package(default_visibility = ["//java/arcs:allowed-packages"])

arcs_kt_jvm_library(
    name = "testutil",
    testonly = True,
    srcs = glob(["*.kt"]),
    deps = [
        "//java/arcs/core/data",
        "//java/arcs/core/storage:storage_key",
        "//java/arcs/core/storage/database",
        "//java/arcs/core/util",
        "//java/arcs/core/util:utils-platform-dependencies",
        "//java/arcs/core/util/performance",
        "//java/arcs/jvm/util",
        "//third_party/kotlin/kotlinx_coroutines",
    ],
)
