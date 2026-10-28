<p align="center"><img src="../../assets/blue-ridge-systems-consulting-logo-wide.svg" alt="Blue Ridge Systems Consulting" width="480"></p>

# codex_file_search

Fast fuzzy file search tool for Codex.

Uses <https://crates.io/crates/ignore> under the hood (which is what `ripgrep` uses) to traverse a directory (while honoring `.gitignore`, etc.) to produce the list of files to search and then uses <https://crates.io/crates/nucleo-matcher> to fuzzy-match the user supplied `PATTERN` against the corpus.
