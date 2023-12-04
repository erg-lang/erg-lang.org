+++
title = "Install"
description = "Install"
weight = 2
+++

# How to Install

By [Ergup](https://github.com/mtshiba/ergup)

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

# Flags

By enabling the `--features` flag, you can customize the installation and build.

- You can change the language of the error message by using  `--features {language}`

```sh
--features japanese
--features simplified_chinese
--features traditional_chinese
```

- Install and build ELS (Erg Language Server)
  - `--features els`
- Debugging mode (for contributors)
  - `--features debug`
- Rich REPL experience (cursor movement, pasting, history, etc.)
  - `--features full-repl`
- Makes the display look better
  - `--features unicode` and `--features pretty`
- Enable all features (exclude features for developers)
  - `--features full`
- See [here](https://github.com/erg-lang/erg/blob/main/doc/EN/dev_guide/build_features.md) for more flags.

# Download Latest Binaries

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/latest/download/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/latest/download/erg-x86_64-unknown-linux-gnu.tar.gz)

[Linux (aarch64)](https://github.com/erg-lang/erg/releases/latest/download/erg-aarch64-unknown-linux-gnu.tar.gz)

[Linux (armv7)](https://github.com/erg-lang/erg/releases/latest/download/erg-armv7-unknown-linux-gnueabihf.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/latest/download/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/latest/download/erg-aarch64-apple-darwin.tar.gz)

# Download Latest Source

[Source URL](https://github.com/erg-lang/erg/releases/latest)

# [Previous Versions](https://github.com/erg-lang/erg/releases)
