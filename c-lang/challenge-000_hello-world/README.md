## Implementation of [Coding Challange 000 - Hello world!](https://azuredvbb.github.io/coding_challenges/challenge_000_hello-world/)

# Notes

### Development environment hurdles

**Code-OSS** is my defacto standard, the only difference was that running on linux, by default, it will take the open marketplace and not the microsoft maintained one.

Fixing it was simple, running on **Arch Linux** the file `/usr/lib/code/product.json` needed to be changed according to this [stackexchange post.](https://stackoverflow.com/questions/64463768/cant-find-certain-extensions-in-code-ossopen-source-variant-of-visual-studio-c).

The `C/C++` plugin was selected (because it was install and forget), whit the build toolchain being `llvm` and `clang` (installed on the system).