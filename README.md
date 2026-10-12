# Homebrew tap for OSIE

[OSIE](https://github.com/deosha/osie) is a local, read-only OS intelligence
engine for macOS and Linux.

```bash
brew install deosha/osie/osie
osie version
osie ask "what is using the most cpu?"
```

The formula installs the prebuilt, checksum-verified release archives
(macOS arm64/x86_64, Linux arm64/x86_64). It is generated from each
release's `SHA256SUMS` by `packaging/homebrew/render_formula.sh` in the main
repository.
