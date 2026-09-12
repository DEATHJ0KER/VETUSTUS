# VETUSTUS 0.2.0-alpha.13 R8

**PRE-BETA · chat/composer localization parity**

R8 is a focused localization release built on the stable R7 feature set.

## What changed

- Default quick phrases are explicitly localized in all 14 selectable UI languages.
- Emoji categories and chat composer tooltips are localized.
- Text formatting / font / FX controls are localized.
- Sticker panel titles/categories and visible sticker labels are localized.
- IRC sticker shortcodes remain stable and language-neutral for interoperability with classic IRC clients.
- Switching the UI language rerenders dynamic quick phrases and sticker labels immediately.
- Added a dedicated regression test that requires explicit chat/composer translations for IT, EN, DE, ES, FR, PT, NL, PL, RU, UK, TR, JA, KO and ZH.

## Preserved from R7

- Native multi-network IRC core.
- Automatic channel LIST once after registration.
- Optional global primary/alternate nickname.
- XDCC Search and Transfer Manager.
- DCC download/resume/upload.
- Internal VETUSTUS Player.
- AI Center with official provider links and Beta responsibility notice.
- vxd.mobi branding and Info / Author section.
- Foreground multilingual Windows setup.

## QA

Automated suite: **71/71 PASS**  
Runtime validator: **PASS**  
i18n audit: **PASS**  
Dedicated 14-language composer coverage: **PASS**

## Installer

`VETUSTUS-0.2.0-alpha.13-setup-x64-R8.exe`

SHA-256:

`2484ecd63e565c000877fb0671efe1c70ef312e10f0dcbedfc26591358601f09`

Official downloads remain on:

https://www.vxd.mobi/vetustus/download/
