load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "encryptionconfig",
    srcs = ["config.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/server/options/encryptionconfig",
    importpath = "k8s.io/apiserver/pkg/server/options/encryptionconfig",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer",
        "//vendor/k8s.io/apimachinery/pkg/util/errors",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/wait",
        "//vendor/k8s.io/apiserver/pkg/apis/config",
        "//vendor/k8s.io/apiserver/pkg/apis/config/v1:config",
        "//vendor/k8s.io/apiserver/pkg/apis/config/validation",
        "//vendor/k8s.io/apiserver/pkg/features",
        "//vendor/k8s.io/apiserver/pkg/server/healthz",
        "//vendor/k8s.io/apiserver/pkg/storage/value",
        "//vendor/k8s.io/apiserver/pkg/storage/value/encrypt/aes",
        "//vendor/k8s.io/apiserver/pkg/storage/value/encrypt/envelope",
        "//vendor/k8s.io/apiserver/pkg/storage/value/encrypt/envelope/kmsv2",
        "//vendor/k8s.io/apiserver/pkg/storage/value/encrypt/identity",
        "//vendor/k8s.io/apiserver/pkg/storage/value/encrypt/secretbox",
        "//vendor/k8s.io/apiserver/pkg/util/feature",
    ],
)
