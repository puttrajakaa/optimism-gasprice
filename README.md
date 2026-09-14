# optimism-gasprice

> op · gas · l2

[![Go 1.22+](https://img.shields.io/badge/go-1.22+-00ADD8)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

Optimism gas helper — derive + stub oracle.

## Features

- ETH derivation path m/44'/60'/0'
- Local vault JSON with XOR wrap
- SHA-256 stand-in keys — no live RPC
- stdlib CLI via flag

## Prerequisites

- Go 1.22+
- Git

## Getting Started

```bash
git clone <repo-url>
cd optimism-gasprice
make build
./bin/opgas -help
```

## CLI Usage

```bash
make test
go run ./cmd/opgas -help
```

## Project Structure

```
cmd/opgas/main.go
internal/config/config.go
internal/crypto/keys.go
internal/wallet/wallet.go
internal/wallet/wallet_test.go
```

## Background

OP stacks search gasprice, not arbitrum-wallet.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![optimism](https://img.shields.io/badge/optimism-111827?style=flat-square) ![gasprice](https://img.shields.io/badge/gasprice-111827?style=flat-square) ![optimism-gasprice](https://img.shields.io/badge/optimism%20gasprice-111827?style=flat-square) ![cryptocurrency](https://img.shields.io/badge/cryptocurrency-111827?style=flat-square) ![wallet](https://img.shields.io/badge/wallet-111827?style=flat-square) ![blockchain](https://img.shields.io/badge/blockchain-111827?style=flat-square) ![web3](https://img.shields.io/badge/web3-111827?style=flat-square) ![bitcoin](https://img.shields.io/badge/bitcoin-111827?style=flat-square)

`optimism` `gasprice` `optimism-gasprice` `cryptocurrency` `wallet` `blockchain` `web3` `bitcoin` `ethereum` `hd-wallet` `open-source` `golang` `go`

Search: optimism-gasprice · op · gas · l2 · Optimism gas helper — derive + stub oracle.

---

<sub>Optimism gas helper — derive + stub oracle.</sub>
