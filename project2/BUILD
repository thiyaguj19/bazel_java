load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "ExampleRunner",
    srcs = glob(["src/main/java/com/example/*.java"]),
    deps = ["//project1:greeter"],
)
