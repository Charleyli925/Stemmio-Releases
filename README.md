# Stemmio Releases

This is the official public distribution channel for Stemmio: signed macOS
installers, automatic-update metadata, release notes, product support and
security reporting.

## Download

Open [the latest release](https://github.com/Charleyli925/Stemmio-Releases/releases/latest)
and download the Apple-silicon (`arm64`) DMG for macOS 12 or later.

Before opening an installer, compare its SHA-256 with the release's
`SHA256SUMS.txt`. Stemmio's updater consumes the signed `latest-mac.yml` and
release ZIP from this repository.

## Source availability

Stemmio source code is proprietary and is maintained in a private repository.
This repository intentionally contains no application source, source archives,
source maps, debug-symbol or crash artifacts, CI logs or build artifacts beyond
the released installer and updater files.
Earlier versions that were published under Apache License 2.0 remain governed
by the license supplied with those historical releases.

## Support and security

- Report reproducible product bugs and feature requests through
  [Issues](https://github.com/Charleyli925/Stemmio-Releases/issues).
- Report suspected vulnerabilities privately through
  [private vulnerability reporting](https://github.com/Charleyli925/Stemmio-Releases/security/advisories/new).
- Do not include confidential HTML, personal data, credentials, local paths or
  full production files in public reports.

See [SUPPORT.md](SUPPORT.md) and [SECURITY.md](SECURITY.md) for the information
to include.
