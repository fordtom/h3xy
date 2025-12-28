# h3xy

Hex file processing library & CLI (HexView alternative/replacement).

## Commands

```bash
cargo build           # Build
cargo check           # Typecheck
cargo test            # Run tests
cargo clippy          # Lint
cargo run -- [args]   # Run CLI
```

## Structure

- `src/lib.rs` - Library exports
- `src/bin/h3xy.rs` - CLI entry point
- `src/` - Core library modules

## Conventions

- Use `thiserror` for error types
- Prefer `u32` for addresses (covers most embedded use cases)
- Tests go in `#[cfg(test)]` modules or `tests/` directory
