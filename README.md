# RustForge

A focused VS Code extension pack for Rust developers who want a clean, practical setup without unnecessary extras.

RustForge installs a small set of extensions that cover the day-to-day Rust workflow: code intelligence, debugging, TOML editing, dependency visibility, and AI-assisted coding.

## Included Extensions

- `rust-lang.rust-analyzer` - Rust language support with navigation, completion, diagnostics, refactoring, and inlay hints.
- `vadimcn.vscode-lldb` - LLDB-based debugging support for Rust binaries, tests, and applications.
- `tamasfe.even-better-toml` - Better editing support for `Cargo.toml`, `rustfmt.toml`, and other TOML files.
- `fill-labs.dependi` - Dependency insight inside manifest files to help keep packages easier to understand and maintain.
- `anthropic.claude-code` - AI-assisted coding workflows for exploring, editing, and iterating on Rust projects.

## Why This Pack

- Keeps the toolset intentionally small and easy to trust.
- Covers the core Rust workflow most developers need on a fresh machine.
- Works well as a baseline for personal projects, learning, and team onboarding.
- Leaves room to add specialized extensions only when a project actually needs them.

## Best For

- Developers setting up Rust in VS Code for the first time
- Teams standardizing on a lean default extension set
- Learners who want a strong Rust workflow without a long extension list

## What This Pack Does Not Include

This extension pack installs editor extensions only. It does not install the Rust toolchain itself.

Before you start, make sure your machine has:

- `rustup`
- `rustc`
- `cargo`
- a working LLDB environment for your platform

## Quick Start

1. Install the pack from the VS Code Marketplace.
2. Install the Rust toolchain with `rustup` if it is not already available on your machine.
3. Open a Rust workspace and let `rust-analyzer` finish indexing the project.
4. Use VS Code's `Run and Debug` view to launch or attach with CodeLLDB.
5. Edit `Cargo.toml` with TOML support and dependency insight already in place.

## Philosophy

RustForge is intentionally opinionated: start with a lean, high-value baseline first, then add niche tools only when your project calls for them.

## License

MIT
