# ezforge CLI

Public release distribution for the `ezforge` command-line tool — the official CLI for [ezForge Platform](https://ezforge.ai).

➡️ **[Download the latest release](https://github.com/ezforgeai/ezforge-cli/releases/latest)**

## Install

### Homebrew (macOS / Linux)

```bash
brew install ezforgeai/tap/ezforge
```

### Direct download

Grab the platform-specific archive from the [latest release](https://github.com/ezforgeai/ezforge-cli/releases/latest), extract, and move `ezforge` onto your `$PATH`. Verify with `checksums.txt`.

Supported platforms:

| OS      | Architecture          | Asset                                 |
|---------|-----------------------|---------------------------------------|
| macOS   | arm64 (Apple Silicon) | `ezforge_<version>_darwin_arm64.tar.gz` |
| macOS   | amd64 (Intel)         | `ezforge_<version>_darwin_amd64.tar.gz` |
| Linux   | amd64                 | `ezforge_<version>_linux_amd64.tar.gz`  |
| Linux   | arm64                 | `ezforge_<version>_linux_arm64.tar.gz`  |
| Windows | amd64                 | `ezforge_<version>_windows_amd64.zip`   |
| Windows | arm64                 | `ezforge_<version>_windows_arm64.zip`   |

## Verify

```bash
ezforge --version
```

## Documentation

- [Quickstart](https://docs.ezforge.ai/getting-started/quickstart)
- [CLI Reference](https://docs.ezforge.ai/cli-reference/overview)

## About this repository

This repository is the **public distribution channel** for the `ezforge` CLI. Source code lives in the private `ezforgeai/ezRyder` monorepo; releases here are published automatically by [GoReleaser](https://goreleaser.com). No issues, pull requests, or source code are accepted here — please use the documentation portal or contact ezForge support.
