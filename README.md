# core-swag releases

Prebuilt binaries for `core-swag`, a CLI that generates OpenAPI specs from Go code.
This repo only hosts release assets; see [Releases](https://github.com/griffnb/core-swag-releases/releases).

## Install

```sh
curl -fsSL https://github.com/griffnb/core-swag-releases/releases/latest/download/install.sh | sh
```

Supports Linux and macOS on amd64/arm64 and verifies the download against `checksums.txt`.
Options: `VERSION=v0.0.1` to pin a version, `INSTALL_DIR=/some/dir` to choose where it goes.
Windows: download the `.zip` for your architecture from the latest release.
