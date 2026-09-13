# VETUSTUS 0.2.0-alpha.13 R8

**PRE-BETA · 14-language chat/composer parity · signed Beta authorization**

R8 is the current public Pre-Beta build, preserving the stable R7 feature set while completing the chat/composer localization pass and adding automatic signed Beta authorization through `vxd.mobi`.

## What changed

- Default quick phrases are explicitly localized in all 14 selectable UI languages.
- Emoji categories and chat composer tooltips are localized.
- Text formatting / font / FX controls are localized.
- Sticker panel titles/categories and visible sticker labels are localized.
- IRC sticker shortcodes remain stable and language-neutral for interoperability with classic IRC clients.
- Switching the UI language rerenders dynamic quick phrases and sticker labels immediately.
- Added a dedicated regression test that requires explicit chat/composer translations for IT, EN, DE, ES, FR, PT, NL, PL, RU, UK, TR, JA, KO and ZH.
- Added automatic Beta authorization through the official `vxd.mobi` service.
- Authorization responses are signed with Ed25519 and verified by the client.
- No account, email address, activation code or manual activation dialog is required.
- Authorization status is exposed in **Settings → Info / Author**.

## Localization scope

VETUSTUS exposes 14 selectable UI languages. R8 guarantees explicit 14/14 coverage for the chat/composer surface listed above. Some advanced Pre-Beta strings in secondary locales can still use the English fallback; application-wide 14-language parity is therefore not claimed yet.

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

Automated suite: **74/74 PASS**  
Runtime validator: **PASS**  
i18n audit: **PASS**  
Dedicated 14-language composer coverage: **PASS**  
Signed authorization flow: **validated against the production vxd.mobi endpoint**

## Installer

`VETUSTUS-0.2.0-alpha.13-setup-x64-R8.exe`

SHA-256:

`b44d0427050749ae0ec977979f5891f1f09991ac126105140a5ed253b3057203`

Manual browser ZIP:

`VETUSTUS-0.2.0-alpha.13-R8-Windows-x64.zip`

SHA-256:

`4ebf79cbb659acc207288a4cf907767722d5ccf2df1e8764daeef7ad53885936`

Official downloads remain on:

https://www.vxd.mobi/vetustus/download/
