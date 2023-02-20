# Bazel ToDo

1. Java IDE support other than IntelliJ is a PITA; try the following, in order:
   - Just use IntelliJ?! 😼
   - [bazelbuild/intellij](https://github.com/bazelbuild/intellij/) presumably has code related to classpath - where? (Use IntelliJ to read it!)
   - [salesforce/bazel-java-sdk](https://github.com/salesforce/bazel-java-sdk) may be able to be turned into (#TODO) [a simple CLI (or even Bazel rule)](https://github.com/salesforce/bazel-java-sdk/issues/47) which just updates `java.project.referencedLibraries` in `.vscode/settings.json` / `workspace.code-workspace`?
   - [salesforce/bazel-eclipse](https://github.com/salesforce/bazel-eclipse/) adds Bazel support to Eclipse, but [it doesn't work for me](https://github.com/salesforce/bazel-eclipse/issues/450) (and [other issues](https://github.com/salesforce/bazel-eclipse/issues?q=author%3Avorburger+))
   - [salesforce/bazel-vscode](https://github.com/salesforce/bazel-vscode) adds Bazel support to VSC with Red Hat's Java extension, but [I'm stuck with it](https://github.com/salesforce/bazel-vscode/issues/31)  (and [other issues](https://github.com/salesforce/bazel-vscode/issues?q=author%3Avorburger+))
   - [georgewfraser/java-language-server](https://github.com/georgewfraser/java-language-server) is an alternative LS to Red Hat's Java extension for VSC, with Bazel support built-in, but [has bugs blocking me](https://github.com/georgewfraser/java-language-server/issues?q=author%3Avorburger+)
   - [bazelbuild/vscode-bazel](https://github.com/bazelbuild/vscode-bazel) alone does [not have Java support](https://github.com/bazelbuild/vscode-bazel/issues/281)

1. https://github.com/salesforce/bazel-mystery

1. https://github.com/vorburger/enola/compare/rules_nixpkgs-for-andyscott-misc_rules-shellcheck
   - https://bazel.build/concepts/platforms
   - https://bazel.build/extending/toolchains
