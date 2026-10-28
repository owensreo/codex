<p align="center"><img src="../../../assets/blue-ridge-systems-consulting-logo-wide.svg" alt="Blue Ridge Systems Consulting" width="480"></p>

# Windows exec-server fixture

This directory contains the small Windows exec-server binary used by
foreign-OS tests. It links only `codex-exec-server` because the full Codex
Windows graph does not yet cross-build with Bazel.
