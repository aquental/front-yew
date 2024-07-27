# Front Yew
Front demo using Rust and WASM

#### Install [Trunk](https://trunkrs.dev/)
```Script
rustup target add wasm32-unknown-unknown
cargo install --locked trunk
```

#### Install cargo-generate
```Script
cargo install cargo-generate
```

#### Generate yew skeleton app
```Script
cargo generate --git https://github.com/yewstack/yew-trunk-minimal-template
cargo new yew-app
cd yew-app
```
