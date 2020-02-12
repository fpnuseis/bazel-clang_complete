# bazel-cmakelists

The workaround script to generate a `.clang_complete` from [Bazel](https://bazel.io) C++ target.

## Usage

```
bazel-clang_complete --targets <bazel-target>
```

e.g.

```
bazel-clang_complete --targets //test/...
```

## Requirements
- Python 2.7
- Bazel 0.17+
