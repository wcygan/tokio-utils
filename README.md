# Tokio Utils

[<img alt="github" src="https://img.shields.io/badge/github-wcygan/tokio--utils-8da0cb?style=for-the-badge&labelColor=555555&logo=github" height="20">](https://github.com/wcygan/tokio-utils)
[<img alt="crates.io" src="https://img.shields.io/crates/v/tokio-utils.svg?style=for-the-badge&color=fc8d62&logo=rust" height="20">](https://crates.io/crates/tokio-utils)
[<img alt="docs.rs" src="https://img.shields.io/badge/docs.rs-tokio--utils-66c2a5?style=for-the-badge&labelColor=555555&logo=docs.rs" height="20">](https://docs.rs/tokio-utils)
[<img alt="build status" src="https://img.shields.io/github/actions/workflow/status/wcygan/tokio-utils/check.yml?branch=main&style=for-the-badge" height="20">](https://github.com/wcygan/tokio-utils/actions?query=branch%3Amain)

Tools for asynchronous programming in [Tokio](https://tokio.rs/) applications:

#### Resource Pooling
- [Pool](https://docs.rs/tokio-utils/latest/tokio_utils/struct.Pool.html), a shared resource pool.

#### Rate Limiting
- [RateLimiter](https://docs.rs/tokio-utils/latest/tokio_utils/struct.RateLimiter.html), a rate limiter  
- [MultiRateLimiter](https://docs.rs/tokio-utils/latest/tokio_utils/struct.MultiRateLimiter.html), a key-based rate limiter

#### Graceful Shutdown
- [ShutdownController](https://docs.rs/tokio-utils/latest/tokio_utils/struct.ShutdownController.html), a controller for graceful shutdown  
- [ShutdownMonitor](https://docs.rs/tokio-utils/latest/tokio_utils/struct.ShutdownMonitor.html), a monitor for graceful shutdown

#### Stdin
- [recv_from_stdin](https://docs.rs/tokio-utils/latest/tokio_utils/fn.recv_from_stdin.html), a channel that receives data from stdin

## Usage
Add this to your Cargo.toml:

```toml
[dependencies]
tokio-utils = "0.1.2"
```