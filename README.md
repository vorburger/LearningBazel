# Learning Bazel

[Vorburger](http://www.vorburger.ch) learns [Bazel](https://bazel.build) here.

This repo is organized by folder with isolated standalone examples, each of which has its own README. There is intentionally no `WORKSPACE` file in the root directory.

Pre-requisite: Install [Bazelisk](https://github.com/bazelbuild/bazelisk), e.g. [using](https://github.com/vorburger/vorburger-dotfiles-bin-etc/blob/84b1e67e2bd46eb48e31c97bb539b6bd13ed6879/all-install.sh#L40) `go install github.com/bazelbuild/bazelisk@latest` (or e.g. with [eget](https://github.com/zyedidia/eget), or however else you prefer), and `alias b` it. All other required tools for building and testig will then be  automatically downloaded as needed.

`./test` will build and test everything. It's incremental, and should run (very) fast the 2nd time you launch it.

[LearningBazelJavaVSC](https://github.com/vorburger/LearningBazelJavaVSC) is a more Java/VSC specific repo.
