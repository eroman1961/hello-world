# hello-world (Rust)

Minimal Rust example that prints "Hello, world!".

Build & run (requires Rust toolchain / `cargo`):

```powershell
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

```powershell
# recommended: install via the official installer (opens a browser)
iwr https://sh.rustup.rs -UseBasicParsing | iex

# or use winget if available
winget install --id Rust.Rustup -e
```

After installing, open a new terminal and run `cargo run` as shown above.
