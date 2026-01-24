# Lumyn Labs Releases

Official release repository for Lumyn Labs SDK distributions.

## What is this repository?

This repository contains pre-built SDK releases for Lumyn Labs hardware. 
Each release includes headers, compiled libraries, and example projects for 
supported platforms.

## Available SDKs

### Lumyn SDK C
**Latest Version**: v4.1.0 (Released: 2026-01-24)

Pre-built C SDK for integration with C projects.

| Platform | Download |
|----------|----------|
| Linux x64 | [lumyn-sdk-c-v4.1.0-linux-x64.tar.gz](lumyn-sdk-c/v4.1.0/lumyn-sdk-c-v4.1.0-linux-x64.tar.gz) |
| Linux ARM64 | [lumyn-sdk-c-v4.1.0-linux-arm64.tar.gz](lumyn-sdk-c/v4.1.0/lumyn-sdk-c-v4.1.0-linux-arm64.tar.gz) |
| Windows x64 | [lumyn-sdk-c-v4.1.0-windows-x64.tar.gz](lumyn-sdk-c/v4.1.0/lumyn-sdk-c-v4.1.0-windows-x64.tar.gz) |
| macOS ARM64 | [lumyn-sdk-c-v4.1.0-macos-arm64.tar.gz](lumyn-sdk-c/v4.1.0/lumyn-sdk-c-v4.1.0-macos-arm64.tar.gz) |

### Lumyn SDK C++
**Latest Version**: v4.1.0 (Released: 2026-01-24)

Pre-built C++ SDK with modern C++20 APIs.

| Platform | Download |
|----------|----------|
| Linux x64 | [lumyn-sdk-cpp-v4.1.0-linux-x64.tar.gz](lumyn-sdk-cpp/v4.1.0/lumyn-sdk-cpp-v4.1.0-linux-x64.tar.gz) |
| Linux ARM64 | [lumyn-sdk-cpp-v4.1.0-linux-arm64.tar.gz](lumyn-sdk-cpp/v4.1.0/lumyn-sdk-cpp-v4.1.0-linux-arm64.tar.gz) |
| Windows x64 | [lumyn-sdk-cpp-v4.1.0-windows-x64.tar.gz](lumyn-sdk-cpp/v4.1.0/lumyn-sdk-cpp-v4.1.0-windows-x64.tar.gz) |
| macOS ARM64 | [lumyn-sdk-cpp-v4.1.0-macos-arm64.tar.gz](lumyn-sdk-cpp/v4.1.0/lumyn-sdk-cpp-v4.1.0-macos-arm64.tar.gz) |

## Getting Started

1. Download the appropriate SDK for your platform
2. Extract the archive:
   ```bash
   tar -xzf lumyn-sdk-{c|cpp}-v4.1.0-{platform}.tar.gz
   ```
3. See the included README.md for build instructions
4. Explore example projects in the `examples/` directory

## Version History

| Version | Date | Notes |
|---------|------|-------|
| v4.1.0 | 2026-01-24 | Latest release |

## Requirements

- **C SDK**: C11 compatible compiler
- **C++ SDK**: C++20 compatible compiler
- **CMake**: 3.16 or newer (for building examples)

## Documentation

Full documentation: https://docs.lumynlabs.com

## Support

For issues and questions, contact support@lumynlabs.com
