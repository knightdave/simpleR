load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "com_grail_rules_r",
    strip_prefix = "rules_r-0.6.0",
    urls = ["https://github.com/grailbio/rules_r/archive/0.6.0.tar.gz"],
    sha256 = "cd21152c0dade5780271db738b1da85c041c255023d2f791d3c1509a13166ff4"
)

load("@com_grail_rules_r//R:dependencies.bzl", "r_register_toolchains", "r_rules_dependencies")

r_rules_dependencies()

r_register_toolchains()
