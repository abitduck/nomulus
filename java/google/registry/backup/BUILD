package(
    default_visibility = ["//java/google/registry:registry_project"],
)

licenses(["notice"])  # Apache 2.0


java_library(
    name = "backup",
    srcs = glob(["*.java"]),
    deps = [
        "//java/com/google/common/annotations",
        "//java/com/google/common/base",
        "//java/com/google/common/collect",
        "//java/com/google/common/net",
        "//java/com/google/common/primitives",
        "//java/com/google/common/util/concurrent",
        "//third_party/java/appengine:appengine-api",
        "//third_party/java/appengine_gcs_client",
        "//third_party/java/dagger",
        "//third_party/java/joda_time",
        "//third_party/java/json_simple",
        "//third_party/java/jsr305_annotations",
        "//third_party/java/jsr330_inject",
        "//third_party/java/objectify:objectify-v4_1",
        "//third_party/java/servlet/servlet_api",
        "//java/google/registry/config",
        "//java/google/registry/cron",
        "//java/google/registry/model",
        "//java/google/registry/request",
        "//java/google/registry/util",
    ],
)
