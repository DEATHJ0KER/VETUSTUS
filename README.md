# VETUSTUS

**VETUSTUS** is a Windows desktop client for **IRC, XDCC and DCC**, developed as a project of **[vxd.mobi](https://www.vxd.mobi/)** by **VxD aka DEATHJ0KER**.

Current public project snapshot: **0.2.0-alpha.13 R8 · PRE-BETA**.

Project page: https://www.vxd.mobi/vetustus/  
Official downloads: https://www.vxd.mobi/vetustus/download/

> VETUSTUS 0.2 uses its own Native IRC Core. **mIRC is not required and is not bundled.**

## Highlights

- Native multi-network IRC engine with TCP/TLS/STARTTLS, CAP/SASL and NickServ flows.
- Automatic channel discovery with IRC `LIST`, filtering and double-click/Enter join.
- Global optional primary/alternate nickname with per-network fallback.
- Channel/query chat, nicklist, WHOIS, CTCP, Ignore, DCC Send and privilege-aware moderation actions.
- XDCC Search with client-side filters, persistent requests, queue diagnostics and DCC resume.
- Native DCC download, resume and local upload.
- Transfer Manager with progress, ETA, queue state and media actions.
- Internal Player for supported audio/video/images, playlists and library folders.
- Optional AI Center supporting cloud providers, Ollama, LM Studio and custom endpoints.
- Plug-in manager under Settings.
- Diagnostics/self-check/reporting tools.
- 14 selectable UI languages: IT, EN, DE, ES, FR, PT, NL, PL, RU, UK, TR, JA, KO, ZH.
- R8 adds explicit 14-language parity for the chat composer surface: quick phrases, sticker panels/labels, emoji categories, text effects, tooltips and chat filters.
- Some advanced Pre-Beta strings may still fall back to English in secondary locales; full application-wide 14-language parity is not claimed yet.
- HTTPS/SHA-256 update client tied to `vxd.mobi`.

## Documentation

- [Feature overview](docs/FEATURES.md)
- [Quick Start](docs/QUICKSTART.md)
- [R8 release notes](docs/RELEASE-R8.md)
- [R7 release notes](docs/RELEASE-R7.md)
- [Download and hash verification](DOWNLOAD.md)
- [Security policy](SECURITY.md)
- [Project provenance](NOTICE.md)

## Release

Current tested installer: `VETUSTUS-0.2.0-alpha.13-setup-x64-R8.exe`

SHA-256:

`2484ecd63e565c000877fb0671efe1c70ef312e10f0dcbedfc26591358601f09`

The official browser download is distributed from **vxd.mobi**, not GitHub.

## Beta notice

VETUSTUS is free Beta/Pre-Beta software and may contain bugs, incompatibilities or unexpected behavior. Users remain responsible for their own API keys, configuration, automation, plug-ins, files and commands.

**Prima verifica, poi accelera:** vale per una funzione sperimentale quanto per l'overclock della scheda video.

## Repository status

This repository is the official project/development reference for VETUSTUS. Production private keys, API credentials, activation secrets, user data and packaged runtime payloads are intentionally excluded.

Generated installers and downloadable release archives are distributed from `vxd.mobi`, keeping GitHub focused on project provenance, documentation and development material.

## Copyright / source publication

`package.json` declares the project as **UNLICENSED**. Publication of repository contents does not by itself grant a separate open-source license.

Copyright © vxd.mobi / VxD aka DEATHJ0KER.
