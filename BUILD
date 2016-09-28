licenses(["notice"])

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "cjk_tokenizer",
    hdrs = glob(["*.h"],),
    srcs = glob(["*.cc"], exclude = ["test.cc",]),
)

cc_binary(
    name = "cjktest",
    srcs = ["test.cc",],
    deps = [":cjk_tokenizer",],
)

cc_binary(
    name = "cjkexample",
    srcs = ["cjk_tokenizer_example.cc",],
    deps = [":cjk_tokenizer",],
)
