# hello-world (Rust)

Minimal Rust example that prints "Hello, world!".

Build & run (requires Rust toolchain / `cargo`):

```bash
# from the repository root
cd rust
cargo run

# or run without changing directory
cargo run --manifest-path ./rust/Cargo.toml
```

Expected output:

```
Hello, world!
```

If `cargo` is not available on your machine, install Rust using `rustup`:

```bash
# Install via the official installer script (Unix-like systems)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

After installing, open a new terminal and run `cargo run` as shown above.
