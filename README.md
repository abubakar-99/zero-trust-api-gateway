# zero-trust-api-gateway

![Go](https://img.shields.io/badge/Go-1.22-00ADD8?logo=go) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Middleware enforcing per-route auth policies and anomaly detection.

## Overview

This tool provides a production-ready implementation focused on performance, security, and developer experience. Built with modern best practices and designed for real-world deployment.

## Features

- **High performance** — optimized for low latency and high throughput
- **Production ready** — proper error handling, logging, and observability
- **Well tested** — unit and integration tests included
- **Easy to deploy** — Docker support out of the box

## Installation

```bash
git clone https://github.com/abubakar-99/zero-trust-api-gateway
cd zero-trust-api-gateway
go mod tidy
```

## Usage

```bash
go run cmd/main.go
```

## Architecture

```
zero-trust-api-gateway/
├── src/
│   ├── main.go
│   ├── core/
│   └── utils/
├── tests/
├── docs/
├── Dockerfile
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
