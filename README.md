# Aggregatable DKG and VUF

Implementation of "Aggregatable Distributed Key Generation", a distributed key generation (DKG) protocol with aggregatable and publicly verifiable transcripts and a new efficient verifiable unpredictable function (VUF) that can be securely combined with it.

## Installation

Install a recent stable Rust toolchain using [rustup](https://rustup.rs/).

## Testing

Run `cargo test` to test both simple signing and aggregation.

## Benchmarks

Run `cargo bench`.
