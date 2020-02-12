# bazel-clang_complete

The workaround script to generate a `.clang_complete` from [Bazel](https://bazel.io) C++ target.

## Usage

```
bazel-clang_complete --targets <bazel-target>
```

e.g.

```
bazel-clang_complete --targets //test/...
or
bazel-clang_complete --targets //source:exe/envoy-static
```

## Requirements
- Python 2.7
- Bazel 0.17+
