# SolSubs

# Minting instructions
```bash
cargo build-bpf --manifest-path=./mint-nft/programs/Cargo.toml --bpf-out-dir=./dist/program

solana program deploy dist/program/mint.so
```