load("@rules_cc//cc:defs.bzl", "cc_library")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "client",
    hdrs = ["client.h"],
    deps = [
        ":client_base",
    ],
)

cc_library(
    name = "client_base",
    hdrs = ["client_base.h"],
)

cc_library(
    name = "service",
    hdrs = ["service.h"],
    deps = [
        ":service_base",
        "//cyber/scheduler",
    ],
)

cc_library(
    name = "service_base",
    hdrs = ["service_base.h"],
)
