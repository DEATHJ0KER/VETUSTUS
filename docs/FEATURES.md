# VETUSTUS features

Current public project snapshot: **0.2.0-alpha.13 R8 · PRE-BETA**.

VETUSTUS is a Windows desktop client for **IRC, XDCC and DCC** built around its own Native Core. mIRC is not required and is not bundled.

## IRC Native Core

- TCP, TLS and STARTTLS connections
- CAP and SASL PLAIN
- NickServ workflows
- Multi-network sessions
- Channels and private queries
- JOIN / PART / MODE / TOPIC / NAMES / WHO / WHOIS
- CTCP controls and local Ignore
- Privilege-aware moderation actions
- Automatic IRC `LIST` after registration
- Filterable channel list with double-click or Enter to join
- Optional global primary and alternate nickname for all networks

## XDCC and DCC

- XDCC Search with client-side filters
- Persistent XDCC requests
- Queue diagnostics and bot state handling
- DCC download
- DCC resume
- Local DCC upload / DCC Send
- Transfer Manager with progress, ETA and queue information

## Internal Player

Supported audio, video and images can be opened in the internal VETUSTUS Player. The media workflow includes playlists, folders/library, previous/next, shuffle, repeat and optional autoplay.

Actual codec/container playback depends on the Electron/Chromium runtime and codecs available on the system.

## AI Center

AI is optional. VETUSTUS remains a complete IRC/XDCC/DCC client without configuring any AI provider.

Provider surfaces currently include OpenAI, Anthropic Claude, Google Gemini, GroqCloud, OpenRouter, Mistral AI, Cohere, DeepSeek, xAI, Cloudflare Workers AI, Hugging Face, Cerebras, NVIDIA NIM, Together AI, Fireworks AI, Ollama, LM Studio and a custom endpoint.

VETUSTUS does not ship third-party API keys. Users configure their own credentials or local engines.

## Plug-ins and diagnostics

- Plug-in manager under Settings
- Runtime diagnostics and self-checks
- Share-safe diagnostic reports
- Update plumbing served from `vxd.mobi`

## Localization

VETUSTUS exposes 14 selectable UI languages:

IT, EN, DE, ES, FR, PT, NL, PL, RU, UK, TR, JA, KO, ZH.

R8 adds explicit 14-language parity for the **chat/composer surface**, including default quick phrases, sticker panels and visible sticker labels, emoji categories, text effects, tooltips and chat filters.

IRC sticker shortcodes remain language-neutral for interoperability. Some advanced Pre-Beta strings may still use the English fallback in secondary locales, so full application-wide 14-language parity is not claimed yet.

## Project

VETUSTUS is a project of **vxd.mobi**.

Author: **VxD aka DEATHJ0KER**

Project page: https://www.vxd.mobi/vetustus/
