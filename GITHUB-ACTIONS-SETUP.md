# VETUSTUS GitHub Actions build

Il repository GitHub dedicato deve contenere la struttura di questo pacchetto, inclusa:

- `.github/workflows/vetustus-windows-release.yml`
- `resources/app/`
- `server-tools/`

## Build manuale

Apri **Actions → VETUSTUS Windows Release → Run workflow**.

GitHub userà un runner `windows-latest`, installerà Node.js 22, eseguirà test/validator/audit lingue e compilerà:

- `VETUSTUS-<version>-setup-x64.exe`
- `VETUSTUS-<version>-portable-x64.exe`
- `VETUSTUS-<version>-x64.zip`
- `update.json`

Viene inoltre generato un secondo artifact già organizzato per il deploy sotto:

`https://www.vxd.mobi/vetustus/`

## Release automatica

Quando la versione in `resources/app/package.json` è, ad esempio, `0.2.0-alpha.13`, crea e pusha il tag:

```text
git tag v0.2.0-alpha.13
git push origin v0.2.0-alpha.13
```

La pipeline verifica che il tag corrisponda esattamente alla versione del package. In caso positivo crea/aggiorna anche la GitHub Release e allega gli artefatti Windows.

## Upgrade System VETUSTUS

`update.json` continua a puntare esclusivamente a file HTTPS sotto `https://www.vxd.mobi/vetustus/releases/` e contiene SHA-256 e dimensione reali dei binari generati.
