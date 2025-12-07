# Kemu CLI - Binary Releases

This repository contains pre-compiled binaries for the **Kemu CLI** tool.

The Kemu CLI executes Kemu recipes efficiently, automatically managing service dependencies and providing an interactive interface for recipe execution.

## Installation

### Via npm (Recommended)

Install globally using npm:

```bash
npm install -g @kemu-io/kemu-cli
```

After installation, the `kemu` binary will be available in your PATH.

### Direct Binary Download

Download the appropriate binary for your platform from the [Releases](https://github.com/kemu-io/kemu-cli-releases/releases) page:

- **Linux x64**: `kemu-linux-x64`
- **Linux ARM64**: `kemu-linux-arm64`
- **macOS x64**: `kemu-darwin-x64`
- **macOS ARM64 (Apple Silicon)**: `kemu-darwin-arm64`
- **Windows x64**: `kemu-windows-x64.exe`

Make the binary executable (Unix-like systems):

```bash
chmod +x kemu-*
```

Move it to a directory in your PATH:

```bash
sudo mv kemu-* /usr/local/bin/kemu
```

## Quick Start

1. Execute a Kemu recipe:
   ```bash
   kemu run ./recipe.kemu
   ```

2. With environment variables:
   ```bash
   kemu run ./recipe.kemu --env .env
   ```

## License

Proprietary software copyright (c) Kemu Platform. All rights reserved.
