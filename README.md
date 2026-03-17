# iPhone Userscripts

Personal archive of userscripts for Safari on iPhone and other mobile browsers that support Tampermonkey-style metadata blocks.

## What is in this repo

This repository stores script snapshots as `.txt` files. Each file contains a standard `// ==UserScript==` header and can be imported into a compatible userscript manager.

Current scripts:

- `AIO Video Downloader.txt`
- `Additional Bypasses.txt`
- `Anti-Adblocker.txt`
- `Bypass Shortlinks.txt`
- `Chat GPT Tools.txt`
- `Direct Links Out.txt`
- `Easy Offline.txt`
- `Export AI Chat to Markdown.txt`
- `GH Ultimate.txt`
- `HTML5 Video Tools.txt`
- `Immersive Translate.txt`
- `Infinite Scroll.txt`
- `Life Web Restrictions.txt`
- `PicView CE+.txt`
- `PicView.txt`
- `True URL Downloader.txt`

## Recommended use on iPhone

1. Install a Safari-compatible userscript manager on iPhone or iPad.
2. Open the script file you want from this repo.
3. Import or paste the script into your userscript manager.
4. If the app requires a `.user.js` file, rename a copy of the script before importing it.
5. Enable the Safari extension and allow it on the sites you want to use.

## Before enabling a script

- Review the `@match`, `@include`, `@grant`, `@connect`, `@downloadURL`, and `@updateURL` fields.
- Treat these files as snapshots. Some scripts appear to be third-party copies and may update upstream independently.
- Test one script at a time. Several of these modify page behavior aggressively and can conflict with each other.
- Be careful with broad scripts such as translators, downloaders, and adblock bypass tools, especially on sites that require login.

## Repo conventions

- Keep script snapshots in the repository root unless there is a strong reason to reorganize.
- Prefer preserving upstream metadata headers.
- Use clear filenames that match the script name shown in the metadata block.
- Keep line endings as LF so edits stay clean across Linux, macOS, and synced devices.

## Notes

- This repo does not currently define upstream sources or licenses for each script.
- If you plan to publish this beyond personal use, add provenance and licensing information per script before redistributing it.
