<p align="center"><img src="../../assets/blue-ridge-systems-consulting-logo-wide.svg" alt="Blue Ridge Systems Consulting" width="480"></p>

# codex-client

Higher-level request policy layered on `codex-http-client` without any Codex/OpenAI API awareness.

- Provides retry utilities (`RetryPolicy`, `RetryOn`, `run_with_retry`, `backoff`) that callers plug into for unary and streaming calls.
- Supplies the `sse_stream` helper to turn byte streams into raw SSE `data:` frames with idle timeouts and surfaced stream errors.
- Defines the request telemetry callback used by higher-level clients.
- Re-exports the low-level HTTP types temporarily so consumers can migrate to `codex-http-client` incrementally.
