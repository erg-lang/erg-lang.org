+++
title = "Install"
description = "Install"
weight = 2
+++

# Way to install

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
 -  Debugging mode (for contributors)
    -  `--features debug`
 -  Rich REPL experience (cursor movement, pasting, history, etc.)
    - `--features full-repl`
 - Makes the display look better
    - `--features unicode` and `--features pretty`
 - Enable all features (exclude features for developers)
    - `--features full`
 - See [here](https://github.com/erg-lang/erg/blob/main/doc/EN/dev_guide/build_features.md) for more flags.

# Download Binary

## 0.6.4

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.4/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.4/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.4/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.6.4/erg-aarch64-apple-darwin.tar.gz)

## 0.6.3

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.3/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.3/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.3/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.6.3/erg-aarch64-apple-darwin.tar.gz)

## 0.6.2

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.2/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.2/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.2/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.6.2/erg-aarch64-apple-darwin.tar.gz)

## 0.6.1

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.1/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.1/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.1/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.6.1/erg-aarch64-apple-darwin.tar.gz)

## 0.6.0

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.0/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.0/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.6.0/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.6.0/erg-aarch64-apple-darwin.tar.gz)

## 0.5.13

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.13/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.13/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.13/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.13/erg-aarch64-apple-darwin.tar.gz)

## 0.5.12

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.12/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.12/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.12/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.12/erg-aarch64-apple-darwin.tar.gz)

## 0.5.11

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.11/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.11/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.11/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.11/erg-aarch64-apple-darwin.tar.gz)

## 0.5.10

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.10/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.10/erg-x86_64-unknown-linux-gnu.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.10/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.10/erg-aarch64-apple-darwin.tar.gz)

## 0.5.9

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.9/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.9/erg-x86_64-unknown-linux-gnu.tar.gz)

[Linux (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.9/erg-aarch64-unknown-linux-gnu.tar.gz)

[Linux (armv7)](https://github.com/erg-lang/erg/releases/download/v0.5.9/erg-armv7-unknown-linux-gnueabihf.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.9/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.9/erg-aarch64-apple-darwin.tar.gz)

## 0.5.8

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.8/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.8/erg-x86_64-unknown-linux-gnu.tar.gz)

[Linux (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.8/erg-aarch64-unknown-linux-gnu.tar.gz)

[Linux (armv7)](https://github.com/erg-lang/erg/releases/download/v0.5.8/erg-armv7-unknown-linux-gnueabihf.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.8/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.8/erg-aarch64-apple-darwin.tar.gz)

## 0.5.7

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.7/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.7/erg-x86_64-unknown-linux-gnu.tar.gz)

[Linux (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.7/erg-aarch64-unknown-linux-gnu.tar.gz)

[Linux (armv7)](https://github.com/erg-lang/erg/releases/download/v0.5.7/erg-armv7-unknown-linux-gnueabihf.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.7/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.7/erg-aarch64-apple-darwin.tar.gz)

## 0.5.6

[Windows (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.6/erg-x86_64-pc-windows-msvc.zip)

[Linux (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.6/erg-x86_64-unknown-linux-gnu.tar.gz)

[Linux (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.6/erg-aarch64-unknown-linux-gnu.tar.gz)

[Linux (armv7)](https://github.com/erg-lang/erg/releases/download/v0.5.6/erg-armv7-unknown-linux-gnueabihf.tar.gz)

[MacOS (x86_64)](https://github.com/erg-lang/erg/releases/download/v0.5.6/erg-x86_64-apple-darwin.tar.gz)

[MacOS (aarch64)](https://github.com/erg-lang/erg/releases/download/v0.5.6/erg-aarch64-apple-darwin.tar.gz)

# Download Source

## 0.6.4

[Source(zip)](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.4.zip)

[Source(tar)](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.4.tar.gz)

## 0.6.3

[Source(zip)](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.3.zip)

[Source(tar)](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.3.tar.gz)


## 0.6.2

[Source(zip)](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.2.zip)

[Source(tar)](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.2.tar.gz)

## 0.6.1

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.1.zip)

## 0.6.0

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.6.0.zip)

## 0.5.13

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.13.zip)

## 0.5.12

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.12.zip)

## 0.5.11

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.11.zip)

## 0.5.10

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.10.zip)

## 0.5.9

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.9.zip)

## 0.5.8

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.8.zip)

## 0.5.7

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.7.zip)

## 0.5.6

[Source](https://github.com/erg-lang/erg/archive/refs/tags/v0.5.6.zip)