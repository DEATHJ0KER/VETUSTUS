# Download VETUSTUS

Official VETUSTUS downloads are distributed from **vxd.mobi**:

https://www.vxd.mobi/vetustus/download/

Current public Beta line: **0.2.0-alpha.13 R8 · PRE-BETA**

## Verify your download

Current R8 setup:

`VETUSTUS-0.2.0-alpha.13-setup-x64-R8.exe`

SHA-256:

`b44d0427050749ae0ec977979f5891f1f09991ac126105140a5ed253b3057203`

Manual browser ZIP:

`VETUSTUS-0.2.0-alpha.13-R8-Windows-x64.zip`

SHA-256:

`4ebf79cbb659acc207288a4cf907767722d5ccf2df1e8764daeef7ad53885936`

The website may offer the ZIP wrapper for manual browser download. The VETUSTUS updater uses the direct setup EXE because it verifies the installer hash before launching it.

## Automatic Beta authorization

The current R8 build performs an automatic authenticity/authorization check with the official `vxd.mobi` service. No account, email address, license key or manual activation dialog is required.

Authorization is signed with Ed25519 and the current state can be viewed in **Settings → Info / Author**.

## R8 localization note

R8 explicitly localizes the chat/composer surface across all 14 selectable UI languages: default quick phrases, sticker categories and visible labels, emoji categories, text effects, tooltips and chat filters. IRC sticker shortcodes remain language-neutral for interoperability.

## Windows warning

The Beta may trigger SmartScreen/reputation warnings if the installer is not signed with a public Authenticode certificate. Verify the source URL and SHA-256. Do not disable antivirus or SmartScreen globally just to run VETUSTUS.

GitHub is the official project/development reference. **Release binaries are intentionally distributed from vxd.mobi.**
