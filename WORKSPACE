load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "com_grail_rules_r",
    strip_prefix = "rules_r-0.5.0",
    urls = ["https://github.com/grailbio/rules_r/archive/0.5.0.tar.gz"],
    sha256 = "f4976b7bd9c99a2bae0b2cb625cf4a77a37107b0c4bd802c0d140ca0e27f730a"
)

load("@com_grail_rules_r//R:dependencies.bzl", "r_register_toolchains", "r_rules_dependencies")

r_rules_dependencies()

r_register_toolchains()