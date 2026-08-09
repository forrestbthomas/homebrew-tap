# Homebrew Tap for pi-harness

This tap provides the **pi-run** CLI from [pi-harness](https://github.com/forrestthomas/pi-harness) — a provider-agnostic coding-agent harness + DeepEval evaluation suite.

## Install

```bash
brew install forrestbthomas/tap/pi-run
```

Or tap first, then install:

```bash
brew tap forrestbthomas/tap
brew install pi-run
```

The formula downloads the prebuilt binary matching your OS/architecture from the
latest [pi-harness release](https://github.com/forrestbthomas/pi-harness/releases).

## Update

```bash
brew upgrade pi-run
```

## Verify

```bash
pi-run version
pi-run --help
```

## Why Homebrew?

Installing via Homebrew avoids macOS Gatekeeper's "Apple could not verify"
warning for unsigned binaries downloaded directly from GitHub. Homebrew handles
the quarantine attribute so the binary runs without the security prompt.
