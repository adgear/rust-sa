[![Build Status](https://travis-ci.org/oli-obk/rust-sa.svg?branch=master)](https://travis-ci.org/oli-obk/rust-sa)
[![Latest Version](https://img.shields.io/crates/v/static_assert.svg)](https://crates.io/crates/static_assert)

##Example usage

```rust
#![feature(plugin)]
#![plugin(static_assert)]

fn main() {
    static_assert!(5 == 4);
}
```
