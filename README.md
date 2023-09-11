
# Bazel sample: JVM

[Buildless](https://less.build), [Bazel](https://bazel.build), and JVM.

## Details about this sample

This sample code uses the [Bazel](https://bazel.build) build tool to build a JVM project, with support for build caching via [Buildless](https://less.build). Bazel is a fantastic tool which is very good at caching previously-built code, and Buildless is a super fast remote build cache and CDN.

## Running this sample

It's a regular Bazel codebase. You can just do:

```
# with Bazelisk installed...
bazel build //...
```
