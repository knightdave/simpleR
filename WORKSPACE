load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "com_grail_rules_r",
    strip_prefix = "rules_r-0.5.9",
    urls = ["https://github.com/grailbio/rules_r/archive/0.5.9.tar.gz"],
    sha256 = "24ab5030ec138af021e8c7cf25abeb028e2b95283e05c7dff38b13a405ddb3f7"
)

load("@com_grail_rules_r//R:dependencies.bzl", "r_register_toolchains", "r_rules_dependencies")

r_rules_dependencies()

r_register_toolchains()