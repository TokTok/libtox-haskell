load("@io_tweag_rules_haskell//haskell:haskell.bzl", "haskell_library")

haskell_library(
    name = "hs-toxcore-c",
    srcs = glob(["src/**/*.*hs"]),
    prebuilt_dependencies = [
        "base",
        "bytestring",
    ],
    src_strip_prefix = "src",
    deps = [
        "@haskell_data_default_class//:data-default-class",
    ],
)
