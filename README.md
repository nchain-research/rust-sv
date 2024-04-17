# nChain Rust-SV
![Test Status](https://gist.githubusercontent.com/Danconnolly/ba7b66a3f55b19ca69abe8b8b537ae56/raw/badge.svg)
[![dependency status](https://deps.rs/repo/github/nchain-research/rust-sv/status.svg)](https://deps.rs/repo/github/nchain-research/rust-sv)

This is the nChain fork of the rust-sv library. The original library can be found at 
[https://github.com/brentongunning/rust-sv].  

We've created this repository because the original source doesn't appear to be updated anymore. This repository
contains some critical updates. We will feed updates here back to the original repository as pull-requests. The
purpose is to maintain the rust-sv library, not to extend it. Fixes should be limited to those that are necessary
to keep the library working with the latest versions of Rust and its dependencies.

The nChain version is available in the `nchain` branch. The `master` branch is the original version.

To use this version in your project, use a line such as the following in your `Cargo.toml` file:

```toml
sv = { git = "https://github.com/nchain-research/rust-sv.git", branch = "nchain" }
```

nChain versions are tagged with a version number preceded by `n`, for example `n0.2.3`.

# Original Text

A library to build Bitcoin SV applications and infrastructure in Rust.

[Documentation](https://docs.rs/sv/)

Features

* P2P protocol messages (construction and serialization)
* Address encoding and decoding
* Transaction signing
* Script evaluation
* Node connections and basic message handling
* Wallet key derivation and mnemonic parsing
* Mainnet and testnet support
* Various Bitcoin primitives
* Genesis upgrade support

# Installation

Add ```sv = "0.2"``` to Cargo.toml

# Known limitations

This library should not be used for consensus code because its validation checks are incomplete.

# License

rust-sv is licensed under the MIT license.
