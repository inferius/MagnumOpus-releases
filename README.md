# MagnumOpus Explorer - releases

Fast file manager for Windows. This repository only hosts the builds
(installer and portable ZIP) and the update manifests; there is no source
code here.

**Download:** [Releases](https://github.com/inferius/MagnumOpus-releases/releases)
- `MagnumOpus-<version>-setup.exe` - installer (per user, no admin rights)
- `MagnumOpus-<version>.zip` - portable build

The app updates itself: it checks `channels/<channel>.json` once a day,
verifies its Ed25519 signature and the SHA-256 of the package, downloads in
the background and offers a restart. No telemetry - the check is a single
GET of a static file.

The builds are not code-signed yet, so Windows SmartScreen may show
"Windows protected your PC" - click **More info -> Run anyway**.

Support the development: [Ko-fi](https://ko-fi.com/inferiusx) (voluntary, nothing is limited without it).

---

# MagnumOpus Explorer - vydání

Rychlý správce souborů pro Windows. Tento repozitář obsahuje jen sestavení
(instalátor a přenosný ZIP) a manifesty aktualizací; zdrojový kód tu není.

**Stažení:** [Releases](https://github.com/inferius/MagnumOpus-releases/releases)
- `MagnumOpus-<verze>-setup.exe` - instalátor (pro uživatele, bez práv správce)
- `MagnumOpus-<verze>.zip` - přenosná verze

Aplikace se aktualizuje sama: jednou denně zkontroluje
`channels/<kanál>.json`, ověří jeho podpis Ed25519 a otisk SHA-256 balíčku,
stáhne na pozadí a nabídne restart. Žádná telemetrie - kontrola je jediné
stažení statického souboru.

Sestavení zatím nejsou podepsaná certifikátem, takže Windows SmartScreen
může ukázat „Systém Windows ochránil váš počítač“ - klikni na **Další
informace -> Přesto spustit**.

Podpora vývoje: [Ko-fi](https://ko-fi.com/inferiusx) (dobrovolně, bez příspěvku se nic neomezuje).
