# Uptime Kuma

[![CI](https://github.com/leberkaslabs/uptime-kuma/actions/workflows/ci.yml/badge.svg)](https://github.com/leberkaslabs/uptime-kuma/actions/workflows/ci.yml)

This repository contains the Docker Compose setup for Uptime Kuma - an easy-to-use self-hosted monitoring tool.

## Requirements

- Make sure Docker and Docker Compose are installed on your system.
- Be sure to check out [Uptime Kuma](https://uptimekuma.org/) - its awesome!

## Installation

The installation is straightforward. Simply clone this repository and start Uptime Kuma using Docker Compose:

```bash
# Clone this repository
git clone https://github.com/leberkaslabs/uptime-kuma.git

# Change into repository
cd uptime-kuma

# Startup Uptime Kuma
docker compose up -d
```

## Advanced Configuration

You can customize your setup using a Docker Compose override file:

```bash
# Create a Docker Compose override file
cp example.compose.override.yml compose.override.yml

# Recreate and apply the configuration
docker compose up -d --force-recreate
```

## License

Copyright © 2025 Niclas Spreng

Licensed under the [MIT license](LICENSE).
