+++
title = "Erg Programming Language"
+++
# Features
- Robustness
- Readability
- Productivity
- Programmer Friendly
- Multi Paradigm
  - Functional & Object-Oriented & Meta-Programming
- Incrementally improve your Python codebase
- Multiple Backends
  - CPython
  - __WIP__ Dyne(Python compatible bytecode interpreter)
  - __WIP__ Gal(LLVM backend)
- __WIP__ Compiler optimized reference counting for Erg code not using the Python ecosystem.

# Installation
By Cargo: `cargo install erg`

By Srouce: `cargo build --release`

Erg supports building with Nix

__Flag:__ 
 - By enabling the `--features` flag, you can change the language in which error messages are displayed:
   - `--features japanese`
   - `--features simplified_chinese`
   - `--features traditional_chinese`
 - Debugging mode (for contributors)
   - `--features debug`

# Community 

## [Discord](https://discord.gg/zfAAUbgGr4)

## [Github Discussions](https://github.com/erg-lang/erg/discussions)