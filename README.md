[![Build status][travis-image]][travis-url]

[travis-image]:
https://travis-ci.org/solana-labs/solana-program-library.svg?branch=master
[travis-url]: https://travis-ci.org/solana-labs/solana-program-library

# SPL Token Program

Full documentation is available at <https://spl.solana.com/token>

## Development

### Environment Setup

1. Install the latest Rust stable from <https://rustup.rs/>
2. Install Solana v1.6.1 or later from <https://docs.solana.com/cli/install-solana-cli-tools>
3. Install the `libudev` development package for your distribution (`libudev-dev` on Debian-derived distros, `libudev-devel` on Redhat-derived).

### Build

The normal cargo build is available for building programs against your host machine:

```rust
cargo build
```

To build the token program for the Solana BPF target:

```rust
cd dosh
cargo build-bpf
```
