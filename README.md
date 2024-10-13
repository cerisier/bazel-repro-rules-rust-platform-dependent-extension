# Instructions

1. Run `bazel mod deps --lockfile_mode=update`
2. Run`docker run -it -v $(pwd):/src/workspace -w /src/workspace gcr.io/bazel-public/bazel:latest bazel mod deps --lockfile_mode=update`
3. Observe `MODULE.bazel.lock` changes
