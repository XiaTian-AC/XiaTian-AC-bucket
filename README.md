# XiaTian-AC-bucket

Personal Scoop bucket for XiaTian-AC projects — a single shared bucket for
multiple apps. Currently hosts **faster-dooit** (installs as the `fdooit`
command).

## Usage

```powershell
scoop bucket add faster-dooit https://github.com/XiaTian-AC-bucket
scoop install faster-dooit
```

## Contents

| App | Manifest | Command |
|---|---|---|
| faster-dooit | `faster-dooit.json` | `fdooit` |

## What is faster-dooit?

A vim-style TUI todo manager written in Go. **Unaffiliated with the
[dooit](https://github.com/dooit-org/dooit) project** — this is an independent,
from-scratch reimplementation. AI-assisted hobby project by a middle-school
student developer.

Source: https://github.com/XiaTian-AC/faster-dooit

## Maintenance

Manifests in this bucket are **auto-updated by each project's release CI**:
every `vX.Y.Z` tag rebuilds and pushes a fresh manifest with the correct
SHA256. See `.scoop/faster-dooit.json.tmpl` in the source repo for the
template.