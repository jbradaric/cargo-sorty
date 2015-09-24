# cargo-sorty

`cargo sorty` runs [sorty] on the current project.
This is a fork of [cargo-clippy].


**NOTE:** requires nightly Rust.


## Installation

First compile with `cargo build --release`, then add
`target/release/cargo-sorty` into your `$PATH`.

**WARNING:** simply copying it is not enough; you must
specifically add the directory to your path, or use
a symbolic link instead.


[sorty]: https://github.com/Wafflespeanut/rust-sorty
[cargo-clippy]: https://github.com/arcnmx/cargo-clippy
