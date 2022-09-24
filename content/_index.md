+++
title = "Erg Programming Language"
+++

# Features

- __Robustness__

  Erg has a strong type system. For example, it has dependent types and refinement types. These types strongly encode pre-conditions, invariant conditions, etc. into the code.

- __Readability__

  Erg defines a rich set of methods and functions by default. This reflects the readability of Erg code.

- __Programmer Friendly__

  Erg is committed to providing error messages that are easy to read. Erg also provide multilingual support for error messages.

- __Multi Paradigm__
  - Functional & Object-Oriented

- __Incrementally improve your Python codebase__

  Erg code can be compiled into Python bytecode. This means you have zero-cost access to your Python assets with Erg. It is also easy to type and call Python APIs, like TypeScript.

- __Multiple Backends__
  - CPython
  - __WIP__ Dyne (Python compatible bytecode interpreter)
  - __WIP__ Gal (LLVM backend)

# Installation

By Cargo (Rust package manager):

```sh
cargo install erg
```

By Source (Need to install the Rust toolchain):

```sh
git clone https://github.com/erg-lang/erg.git
cd erg
cargo build --release
```

And Erg supports building with [Nix](https://github.com/erg-lang/erg#building-by-nix).

__Flags:__

 - By enabling the `--features` flag, you can change the language in which error messages are displayed:
   - `--features japanese`
   - `--features simplified_chinese`
   - `--features traditional_chinese`
 - Debugging mode (for contributors)
   - `--features debug`