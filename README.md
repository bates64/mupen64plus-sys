# mupen64plus-sys

Rust bindings to libmupen64plus. Doesn't perform linking as mupen64plus is a shared library.

### Tests

If you don't have `libmupen64plus.(so|dll|dylib)` in your system lib dirs, place it at the root of the repo before running `cargo test`. You can get it for your OS from [GitHub releases](https://github.com/mupen64plus/mupen64plus-core/releases) or build mupen64plus-core from source (`make -C mupen64plus-core/projects/unix/Makefile all`).
