# Front Yew
Front demo using Rust and WASM

#### Install [Trunk](https://trunkrs.dev/)
```Script
rustup target add wasm32-unknown-unknown
cargo install --locked trunk
```

#### Install [cargo-generate](https://github.com/cargo-generate/cargo-generate)
```Script
cargo install cargo-generate
```

#### Generate yew skeleton app
```Script
cargo generate --git https://github.com/yewstack/yew-trunk-minimal-template
cargo new yew-app
cd yew-app
```
#### Update Cargo.toml
```Script
[package]
name = "yew-app"
version = "0.1.0"
edition = "2021"

[dependencies]
# this is the development version of Yew
yew = { git = "https://github.com/yewstack/yew/", features = ["csr"] }
```
#### Create Trunk.toml
```Script
[serve]
# The address to serve on LAN.
address = "127.0.0.1"
# The address to serve on WAN.
# address = "0.0.0.0"
# The port to serve on.
port = 8000
```

#### App
here
