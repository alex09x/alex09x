# Alexander Panasenko

Systems engineer in Los Angeles, California. I work on distributed systems, low-latency
market data, trading infrastructure, AI runtimes and search, mostly in C++, Rust, Go and Python.

Most of my public work sits where those layers meet: collecting and processing data,
coordinating services, and making complex systems usable through APIs and native interfaces.
I prefer explicit limitations and reproducible measurements over claims.

More about me and my projects: [prod.codes/about](https://prod.codes/about/)

## Projects

| Project | What it is |
| --- | --- |
| [**prod-code**](https://github.com/alex09x/prod-code) | Remote code intelligence server for AI coding agents. Your checkout is mirrored to a LAN build node that keeps a warm analyzer (rust-analyzer, gopls, clangd, TypeScript, pyright, sourcekit-lsp) and runs builds and tests there; agents reach it as MCP tools, editors as a language server. [prod.codes](https://prod.codes) |
| [**kyb**](https://github.com/alex09x/kyb) | Know Your Business: a git-backed, searchable knowledge base and incident tracker that serves as shared memory for a fleet of AI agents across sessions and machines. [kybmemory.com](https://kybmemory.com) · [crates.io](https://crates.io/crates/knowyourbusiness) |
| [**rapidfire**](https://github.com/alex09x/rapidfire) | Async MPMC and MPSC channels for Rust, built for WebSocket fan-in, trading bots and other message pipelines; the default build depends only on `std`. [docs.rs](https://docs.rs/rapidfire) · [crates.io](https://crates.io/crates/rapidfire) |
| [**ringfire**](https://github.com/alex09x/ringfire) | Zero-copy, lock-free shared-memory IPC ring buffer and state bus for Linux, the cross-process counterpart to rapidfire; since v0.5.0 a ring can be mirrored to other hosts with the same sequence numbers. [docs.rs](https://docs.rs/ringfire) · [crates.io](https://crates.io/crates/ringfire) |
| [**tako**](https://github.com/alex09x/tako) | GPU-accelerated terminal for macOS 14+ and iOS 17+: a pure-Rust emulation engine with a native Metal renderer, also embeddable as a Swift package. [takocore.com](https://takocore.com) |
| [**mitts**](https://github.com/alex09x/mitts) | Rust-first build system with a machine-wide, content-addressed artifact cache and explicit input tracking; it reads your existing Cargo manifests. Pre-release, Linux and macOS only, no remote cache yet. [mittsbuild.com](https://mittsbuild.com) |

## Contact

- Email: [alex@prod.codes](mailto:alex@prod.codes)
- Web: [prod.codes](https://prod.codes)
