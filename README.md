# WebAssembly

```shell
cargo install wasm-pack
cargo new rust-wasm --lib
wasm-pack build --scope bskyrui # create a pkg folder 
```

## Publish to NPM

```shell
cd pkg
npm publish --access=public
```