# Lode — A Native macOS Markdown Viewer, Diff, Search & Git Tool

Lode is a fast, native **macOS Markdown editor/viewer** built in Rust (Tauri 2)
that renders inline images and code blocks — plus folder diff, full-text search,
and read-only git review, all in one window.

👉 **[rexcode.app/lode](https://rexcode.app/lode/)** · [macOS Markdown editor](https://rexcode.app/lode/macos-markdown-editor/)

This repository hosts the public release builds (DMG) and sample files for Lode.

## Download

- **Latest release:** https://github.com/rex4ssd/lode-releases/releases/latest
- **Mac App Store:** https://apps.apple.com/tw/app/lode-files-diff-search/id6770090457
- **Website & docs:** https://rexcode.app/lode/

## Why Lode

- **Markdown that renders your images.** Inline `![](image.png)` display natively — no broken placeholders.
- **Rust + Tauri 2, not Electron.** A 50 MB note opens fast; very large files stream via mmap.
- **Six modes in one app.** Viewer (Markdown / CSV / XLSX / images / hex), Folder Compare, File Compare, Binary Compare, Search, Git Viewer.
- **Local-first & private.** Works fully offline. Zero telemetry.

## Install (GitHub DMG)

macOS quarantines apps downloaded from the browser. After dragging Lode to `/Applications`, run once:

```bash
xattr -cr /Applications/Lode.app && open /Applications/Lode.app
```

## Links

- Website: https://rexcode.app/lode/
- macOS Markdown editor: https://rexcode.app/lode/macos-markdown-editor/
- Features: https://rexcode.app/lode/features/
- vs Competitors: https://rexcode.app/lode/vs-competitors/
- Pricing: https://rexcode.app/lode/pricing/

---

© RexCode · [rexcode.app](https://rexcode.app/)
