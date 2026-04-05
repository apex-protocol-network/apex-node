# apex-node

Node software for the APEX Layer 1 blockchain.

## Components

| Component | Description |
|-----------|-------------|
| `config` | Configuration loading and validation |
| `p2p` | libp2p-based peer discovery and messaging |
| `rpc` | JSON-RPC server for client interaction |
| `sync` | Chain synchronisation from peers |
| `producer` | Block proposal and transaction ordering |

## Status

> **Pre-alpha.** Initial networking scaffold in development. Single-node devnet: Week 3.

## Requirements

- Rust 1.75+

## Build

```sh
cargo build --release
```

## Running

```sh
apex-node --config devnet.toml
```

## License

[Apache License 2.0](./LICENSE)
