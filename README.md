# datarun

Standalone international mining runtime for Linux x86-64. This repository contains compiled delivery files only.

Verify the binary with `sha256sum -c SHA256SUMS`. The executable takes no runtime arguments. `./datarun --self-check` performs the optional offline self-check.

The binary does not start, stop, or replace an external keepalive. Its bytes match the previously published standalone `run`; this repository change does not modify mining behavior. Downloads of this binary have a fixed digest.

Runtime libraries and delivery metadata are listed in `release.json`. Automatic deployment uses a pinned commit and verifies the expected SHA-256 before execution.
