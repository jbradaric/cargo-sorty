# cargo-sorty

[![travis-badge][]][travis] [![license-badge][]][license]

`cargo sorty` runs [sorty] on the current project.
This is a fork of [cargo-clippy].


**NOTE:** requires nightly Rust.


## Installation

First compile with `cargo build --release`, then add
`target/release/cargo-sorty` into your `$PATH`.

**WARNING:** simply copying it is not enough; you must
specifically add the directory to your path, or use
a symbolic link instead.


[travis-badge]: https://img.shields.io/travis/jbradaric/cargo-sorty/master.svg?style=flat-square
[travis]: https://travis-ci.org/jbradaric/cargo-sorty
[license-badge]: https://img.shields.io/badge/license-MIT-lightgray.svg?style=flat-square
[license]: https://github.com/jbradaric/cargo-sorty/blob/master/LICENSE
[sorty]: https://github.com/Wafflespeanut/rust-sorty
[cargo-clippy]: https://github.com/arcnmx/cargo-clippy
