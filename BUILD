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
