cc_library(
    name = "hello_lib",
    srcs = ["hello.c"],
    hdrs = ["hello.h"],
    visibility = ["//visibility:public"],
)

cc_binary(
    name = "hello_app",
    srcs = ["main.c"],
    deps = [":hello_lib"],
)

cc_test(
    name = "hello_test",
    srcs = ["hello_test.c"],
    deps = [":hello_lib"],
)