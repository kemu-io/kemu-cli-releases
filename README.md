# Kemu CLI - Binary Releases

This repository contains pre-compiled binaries for the **Kemu CLI** tool.

The Kemu CLI executes Kemu recipes efficiently, automatically managing service dependencies and providing an interactive interface for recipe execution.

## Installation

### Quick Install (Recommended)

Use the installation script for automatic setup:

```bash
curl -fsSL https://raw.githubusercontent.com/kemu-io/kemu-cli-releases/main/install.sh | bash
```

This automatically downloads the correct binary for your platform and installs it to `/usr/local/bin`.

### Via npm

Install globally using npm:

```bash
npm install -g @kemu-io/kemu-cli
```

After installation, the `kemu` binary will be available in your PATH.

### Other Installation Methods

For more installation options including:
- Installing specific versions
- Custom installation directories
- Package manager installations (npm, yarn, pnpm, bun)
- Manual installation
- Troubleshooting

See the complete [Installation Guide](INSTALLATION.md).

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
