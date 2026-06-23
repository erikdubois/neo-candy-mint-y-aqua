# CLAUDE.md — neo-candy-mint-y-aqua

## Project overview

Standalone repo for the **neo-candy-mint-y-aqua** folder-icon theme — the same folder set as
`erikdubois/surfn-mint-y-aqua` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-mint-y-aqua/` — folders only. Packaged as `neo-candy-mint-y-aqua-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-mint-y-aqua/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
