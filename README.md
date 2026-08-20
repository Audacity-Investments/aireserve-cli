# aireserve CLI

Pre-built binaries for the `aireserve` CLI — one command connects every coding agent on your machine (Claude Code, Codex) to the AI.Reserve router.

## Install

```bash
curl -fsSL https://get.aireserve.com/install.sh | sh -s -- --router
```

Supported platforms: macOS (arm64, x64), Linux (x64, arm64), Windows (x64).

## Releases

- **Stable** (`vX.Y.Z`): what the installer and `aireserve update` resolve by default.
- **`canary`** (prerelease): rebuilt from the latest main-branch merge; never picked up by default installs. Opt in with `sh -s -- --version canary`.

Source code lives in the private Audacity monorepo; this repository hosts release artifacts only. Issues: contact your AI.Reserve administrator.
