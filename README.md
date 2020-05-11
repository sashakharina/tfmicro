[![docs.rs](https://docs.rs/tfmicro/badge.svg)](https://docs.rs/tfmicro)
[![Crates.io](https://img.shields.io/crates/v/tfmicro.svg)](https://crates.io/crates/tfmicro)

# tfmicro


Tensorflow + `no_std` + Rust = ❤️

The crate contains Rust bindings for the [TensorFlow Micro][]
project. TensorFlow Micro is a version of TensorFlow Lite designed to
run without a standard library, for use on microcontrollers, wasm and
more.

Thanks to [Cargo][] and the [CC crate][], there's no porting required for
new platforms - just drop `tfmicro` into your `Cargo.toml` and
go. You will need a C++ compiler behind the scenes, including for
cross-compiling targets, but in most cases this will be present
already.

## Getting started

Add `tfmicro` in the dependencies section of your `Cargo.toml`

```
[dependencies]
tfmicro = `0.1.0`
```

To understand how the [TensorFlow Micro C examples][c_examples] map to
idiomatic Rust code, see the [Examples](#Examples) section. Otherwise
for a more general description see [Usage](#Usage).

## Examples



## Usage

## Developing

See [DEVELOP.md](DEVELOP.md)

## License

[rust-embedded]: https://www.rust-lang.org/what/embedded
[TensorFlow Micro]: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/micro
[Cargo]: https://doc.rust-lang.org/stable/cargo/
[CC crate]: https://crates.io/crates/cc
[c_examples]: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/micro/examples
