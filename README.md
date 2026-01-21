# About

This repository contains Rust bindings for tonlibjson and services built on top of it.

## ton-grpc

### Docker Setup

You can quickly get started with ton-grpc using Docker. The official Docker image is available on GitHub Container Registry.

**Pull the Docker image:**
```bash
docker pull ghcr.io/getgems-io/ton-grpc
```

**Run the container:**
```bash
docker run --rm -p 50052:50052 ghcr.io/getgems-io/ton-grpc
```

The service will be available on port `50052`.

## ton-liteserver-client
### Installation
```toml
[dependencies]
ton-liteserver-client = { git = "https://github.com/getgems-io/ton-grpc.git" }
tokio = "1.37"
tower = "0.4"
```

### Usage
See `ton-liteserver-client/examples`