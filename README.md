[![CORS - One system. Down to the Core.](https://raw.githubusercontent.com/cors-gmbh/.github/refs/heads/main/cors-banner.jpg)](https://cors.gmbh)

# Pimcore Drive: desktop clients

Downloads of the Pimcore Drive desktop clients for macOS and Windows. They connect Finder and
Explorer to the Pimcore asset tree through the `cors/pimcore-drive` bundle (files on demand,
sync, sign-in through Pimcore Studio).

| Platform | Download |
|---|---|
| macOS 14+ (Apple Silicon) | [PimcoreDrive-macos.dmg](https://github.com/cors-gmbh/pimcore-drive-releases/releases/download/latest/PimcoreDrive-macos.dmg) |
| Windows 10 1903+ / 11 (x64) | [PimcoreDrive-win-x64-setup.exe](https://github.com/cors-gmbh/pimcore-drive-releases/releases/download/latest/PimcoreDrive-win-x64-setup.exe) |
| Windows 10 1903+ / 11 (ARM64) | [PimcoreDrive-win-arm64-setup.exe](https://github.com/cors-gmbh/pimcore-drive-releases/releases/download/latest/PimcoreDrive-win-arm64-setup.exe) |

The release [`latest`](https://github.com/cors-gmbh/pimcore-drive-releases/releases/tag/latest)
always holds the current version of each platform under these names, together with
[`latest.json`](https://github.com/cors-gmbh/pimcore-drive-releases/releases/download/latest/latest.json)
(version, versioned download URL, size and SHA-256 per platform), which the Pimcore Studio plugin
reads. Every version is also kept as its own release (`macos-v<version>`, `windows-v<version>`).

This repository contains no source code. The releases are published by the CI of the private
repository `cors-gmbh/pimcore-drive`.

## License

Copyright (c) CORS GmbH. All rights reserved. The desktop clients are proprietary and closed
source. They are not part of the `cors/pimcore-drive` composer package and are not licensed under
the CORS License (CL) of the bundle. Using, copying or distributing them requires written
permission of CORS GmbH (office@cors.gmbh).
