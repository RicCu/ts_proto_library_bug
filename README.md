# Instructions
Running `bazel build //proto/strip:strip` will succeed but will only generate empty files <br/>
Running `bazel build //proto/nostrip:nostrip` will succeed and will generate the correct files.

This is a modified copy of [rules_nodejs protobuf example](https://github.com/bazelbuild/rules_nodejs/tree/stable/examples/protocol_buffers)
