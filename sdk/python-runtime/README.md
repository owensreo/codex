<p align="center"><img src="../../assets/blue-ridge-systems-consulting-logo-wide.svg" alt="Blue Ridge Systems Consulting" width="480"></p>

# Codex CLI Runtime for Python SDK

Platform-specific runtime package consumed by the published `openai-codex`.

This package is staged during release so the SDK can pin an exact Codex CLI
version without checking platform binaries into the repo.

`openai-codex-cli-bin` is intentionally wheel-only. Do not build or publish an
sdist for this package.
