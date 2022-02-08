# some-cli with some-lib

example code for Rust cli + library

## structure

```
some-cli
├─── .gitignore
├─── Cargo.lock
├─── Cargo.toml
├─── readme.md
├─── some-lib
│    ├─── Cargo.toml
│    └─── src
|         └───lib.rs
├─── src
     └───main.rs
```

## Cargo.toml

```
[package]
name = "some-cli"
version = "0.1.0"
edition = "2021"

[workspace]

[dependencies]
some-lib = { path = "some-lib" }
```