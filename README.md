# Awesome Yggdrasil [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[Yggdrasil](https://yggdrasil-network.github.io) is a self-arranging mesh network with end-to-end encrypted IPv6 routing.

## Contents

- [Implementations and Libraries](#implementations-and-libraries)
- [Mobile and Desktop Clients](#mobile-and-desktop-clients)
- [Messaging and Email](#messaging-and-email)
- [Infrastructure and Services](#infrastructure-and-services)
- [Tools](#tools)
- [Routers and Firmware](#routers-and-firmware)

## Implementations and Libraries

- [Yggdrasil Go](https://github.com/yggdrasil-network/yggdrasil-go) - The original Go implementation.
- [Yggdrasil-ng](https://github.com/Revertron/Yggdrasil-ng) - Rust implementation with CKR (crypto-key routing) support.
- [Ratatoskr](https://github.com/voluminor/ratatoskr) - Go library for embedding Yggdrasil mesh nodes with a userspace gVisor TCP/IP stack.
- [Ygg](https://github.com/asciimoth/ygg) - Fork of Yggdrasil Go focused on embedding as a library, with pluggable transports (QUIC, WebSocket) and extra TUN modes.
- [Yggstack](https://github.com/yggdrasil-network/yggstack) - Go implementation (Netstack instead of TUN).
- [Yggdrasil Lite](https://github.com/vasil646srb/yggdrasil-lite) - Minimal Rust leaf-node implementation for embedded and small Unix devices (OpenWrt, Termux, ESP32), with a `no_std` library build.

## Mobile and Desktop Clients

- [Yggdrasil Android](https://github.com/yggdrasil-network/yggdrasil-android) - Yggdrasil client for Android.
- [Yggstack Android](https://github.com/DrewCyber/yggstack-android) - A full-featured Android UI wrapper for the Yggstack CLI application.
- [Huginn](https://git.shd.company/bubblegum/Huginn) - Yggdrasil client for Windows based on Yggdrasil-ng.

## Messaging and Email

- [Mimir](https://github.com/Mimir-IM/MimirForAndroid) - True P2P messenger on top of Yggdrasil Network.
- [Tyr](https://github.com/JB-SelfCompany/Tyr) - True P2P Email on top of Yggdrasil Network for Android.
- [Yggmail](https://github.com/neilalexander/yggmail) - End-to-end encrypted email for the mesh networking age.

## Infrastructure and Services

- [Alfis](https://github.com/Revertron/Alfis) - Blockchain-based domain system with a built-in DNS server; its .ygg and .anon zones resolve to Yggdrasil addresses only.
- [Public Peers](https://github.com/yggdrasil-network/public-peers) - List of peers that anyone can connect to.
- [Yggpeers](https://gitfield.org/fsky/yggpeers) - Yggdrasil public peers explorer.
- [Yggvault](https://github.com/voluminor/yggvault) - Self-hosted release mirror for Go modules, Composer packages, archives, Web UI, and Yggdrasil-powered node sync.

## Tools

- [Yggprom](https://github.com/yggdrasil-network/yggprom) - Prometheus exporter for Yggdrasil.

## Routers and Firmware

- [MikroTik Yggdrasil Go](https://github.com/litew/mikrotik-yggdrasil-go) - Yggdrasil-go for MikroTik routers.
- [YggMesh](https://github.com/ed-asriyan/YggMesh) - Yggdrasil mesh over Wifi Mesh for blackout scenarios.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](contributing.md) first. Unmaintained projects are kept in [archive.md](archive.md).
