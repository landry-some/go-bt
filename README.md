# go-bt

go-bt is a BitTorrent client implementation written in Go.  
It provides core BitTorrent protocol components including DHT, peer communication, trackers, metadata handling, and file downloading.

The project is designed for learning, experimentation, and exploring the internals of the BitTorrent ecosystem.

---

## Features

- BitTorrent protocol implementation in Go
- DHT (Distributed Hash Table) support
- Peer-to-peer communication
- Tracker communication
- Bencode encoder/decoder
- Metadata handling
- Torrent file downloading
- Modular and extensible architecture

---

## Project Structure

- `bencode/` – Bencode encoding and decoding utilities  
- `dht/` – Distributed Hash Table implementation  
- `downloader/` – Torrent download logic  
- `krpc/` – KRPC protocol implementation (used in DHT)  
- `metainfo/` – Torrent metadata parsing  
- `peerprotocol/` – Peer communication protocol  
- `tracker/` – Tracker interaction logic  
- `internal/helper/` – Shared helper utilities  

---

## Requirements

- Go 1.20+

Install dependencies:

```bash
go mod download
```

---

## Build

```bash
go build ./...
```

---

## Usage

Depending on the entry point provided in the repository, you can run:

```bash
go run .
```

Or build and execute the binary:

```bash
go build -o go-bt
./go-bt
```

(Refer to the code for specific usage patterns and supported commands.)

---

## Learning Goals

This project is suitable for:

- Understanding how BitTorrent works internally
- Exploring DHT and peer-to-peer networking
- Learning network programming in Go
- Studying distributed systems fundamentals

---

## Disclaimer

This project is intended for educational and experimental purposes.  
Ensure compliance with applicable laws and regulations when using BitTorrent technologies.

---
