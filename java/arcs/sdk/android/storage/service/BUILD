load("//third_party/java/arcs/build_defs:build_defs.bzl", "arcs_kt_android_library")

licenses(["notice"])

package(default_visibility = ["//java/arcs:allowed-packages"])

arcs_kt_android_library(
    name = "service",
    srcs = glob(["*.kt"]),
    manifest = "AndroidManifest.xml",
    deps = [
        "//java/arcs/android/common/resurrection",
        "//java/arcs/android/crdt",
        "//java/arcs/android/storage",
        "//java/arcs/android/storage/database",
        "//java/arcs/android/storage/service",
        "//java/arcs/android/storage/service:aidl",
        "//java/arcs/android/storage/ttl",
        "//java/arcs/android/util",
        "//java/arcs/core/analytics",
        "//java/arcs/core/crdt",
        "//java/arcs/core/data",
        "//java/arcs/core/storage",
        "//java/arcs/core/storage/database",
        "//java/arcs/core/storage/driver:driver_providers",
        "//java/arcs/core/storage/keys",
        "//java/arcs/core/util",
        "//java/arcs/core/util/performance",
        "//java/arcs/core/util/statistics",
        "//java/arcs/flags",
        "//java/arcs/jvm/util",
        "//third_party/java/androidx/annotation",
        "//third_party/java/androidx/work",
        "//third_party/kotlin/kotlinx_atomicfu",
        "//third_party/kotlin/kotlinx_coroutines",
    ],
)
