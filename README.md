# bazel java tutorial - this example shows how to build java binary from same and different project folders

### change directory to java-tutorial

bazel build //project1:ProjectRunner --java_runtime_version=remotejdk_11
bazel run //project1:ProjectRunner --java_runtime_version=remotejdk_11

o/p => 
Hi from ExampleGreeting!

bazel build //project2:ExampleRunner --java_runtime_version=remotejdk_11
bazel run //project2:ExampleRunner --java_runtime_version=remotejdk_11

o/p => 
Hi from ExampleGreeting!
Hi from ProjectGreeting!
