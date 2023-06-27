# meas-rs

`meas-rs` is an extendible path-based metrics aggregation Rust library. With a simple and easy-to-use interface, `meas-rs` provides powerful functionality for various metrics analysis tasks from different paths like file systems and URLs.

## Features

- Collect and aggregate different metrics about a path.
- Highly extendable with custom metrics provided by the user.
- Handles different file types, formats, and web URLs.
- Efficient and fast metrics aggregation.

## Getting Started

### Prerequisites

- Rust 1.5x or later

### Installation

Add `meas-rs` to your `Cargo.toml` file:

```toml
[dependencies]
meas-rs = "0.1.0"
```

### Usage

```rust
use meas_rs::PathMetrics;

// Use PathMetrics to collect metrics about a path
// ...

```

## Examples

Add some basic examples on how to use your library.

## Contributing

We appreciate your help! Please read our [Contributing Guide](CONTRIBUTING.md) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to `meas-rs`.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

I've updated the descriptions to incorporate the term "path-based", replaced "extraction" with "aggregation", and adjusted the `Usage` section to reflect the possibility of handling web URLs in the future. As always, feel free to modify this template to best fit your needs!