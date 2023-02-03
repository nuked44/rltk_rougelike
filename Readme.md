# A rougelike in rust

## Based on <https://bfnightly.bracketproductions.com/rustbook/chapter_0.html>

## Run with

cargo build --release --target wasm32-unknown-unknown && wasm-bindgen target/wasm32-unknown-unknown/release/rltk_rougelike.wasm --out-dir wasm --no-modules --no-typescript
