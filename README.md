# VETUSTUS 0.2.0-alpha.13 · SERVERS / UPGRADE / MULTILINGUAL SETUP

**VETUSTUS — Script by VxD aka DEATHJ0KER**

Standalone portable Windows client for IRC, XDCC and DCC. VETUSTUS 0.2 uses its own native networking core: **mIRC is not required and is not bundled**.

Project page: `https://vxd.mobi/vetustus/`


## Alpha.13 · Production hardening

La build installabile viene prodotta con ASAR integrity ed Electron Fuses: `RunAsNode`, `NODE_OPTIONS` e inspector CLI sono disabilitati, l'app carica esclusivamente `app.asar`, i cookie Chromium sono cifrati e DevTools è disattivato nelle build packaged. L'attivazione resta gratuita e automatica, ma ogni token Ed25519 emesso da `vxd.mobi` è legato a installazione, fingerprint Windows, versione e SHA-256 esatto di `app.asar`. Lo stato locale usa `safeStorage`/DPAPI quando disponibile. La chiave privata di firma non viene mai inclusa nel repository o negli artifact.

## Alpha.13 · Server registry / Upgrade / Setup

Questa build rende `servers.ini` autorevole e lo distribuisce con il solo `n0`. L'Upgrade System è vincolato a `https://www.vxd.mobi/vetustus/`, verifica HTTPS e SHA-256, scarica il setup e chiude VETUSTUS prima della sostituzione. Il setup NSIS è predisposto per 14 lingue e trasferisce la lingua scelta al primo avvio dell'interfaccia.

Sono inclusi `BUILD-SETUP.cmd` e `PREPARE-WEB-UPDATE.cmd` per generare rispettivamente il setup Windows e il pacchetto da pubblicare sul sito.

## GitHub Actions / Windows Setup

La alpha.13 include `.github/workflows/vetustus-windows-release.yml`, una pipeline Windows per produrre automaticamente Setup NSIS x64, Portable, ZIP e il bundle `update.json` destinato a `https://www.vxd.mobi/vetustus/`. Vedi `GITHUB-ACTIONS-SETUP.md`.
