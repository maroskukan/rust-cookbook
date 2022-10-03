# Rust Cookbook

## Introduction

Rust is an open-source systems programming language that first appeared in 2010 as Mozilla Research project. It is designed for performance and reliability similar to C++. It is statically and strongly typed and requires compilation. Compiler checks to ensure all memory accesses are valid.


## Documentation

- [Rust Programming Language](https://www.rust-lang.org)


## Installation

The recommended way of installing Rust compiler `rustc`, package manager Cargo `cargo` and documentation `rustup doc` is to use `rustup`. As suggested in documentation you can simply install using the installation script.

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Once installed, verify the compiler version:

```bash
rustc --version
```

You should get output similar to shown below:

```bash
rustc 1.64.0 (a55dd71d5 2022-09-19)
```

In order to update to newer version, simple use the `rustup` with `update` argument.

```bash
rustup update
```



