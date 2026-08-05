# scoop-faster-dooit

Personal Scoop bucket for **faster-dooit** (installs as the `fdooit` command).

## Usage

```powershell
scoop bucket add faster-dooit https://github.com/XiaTian-AC/scoop-faster-dooit
scoop install faster-dooit
```

## What is faster-dooit?

A vim-style TUI todo manager written in Go. **Unaffiliated with the
[dooit](https://github.com/dooit-org/dooit) project** — this is an independent,
from-scratch reimplementation. AI-assisted hobby project by a middle-school
student developer.

Source: https://github.com/XiaTian-AC/faster-dooit

## Maintenance

The manifest in this bucket is **auto-updated by the release CI** in the
faster-dooit repo: every `vX.Y.Z` tag rebuilds and pushes a fresh
`faster-dooit.json` with the correct SHA256. See `.scoop/faster-dooit.json.tmpl`
in the source repo for the template.
