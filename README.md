# Echowa Assist

Application d'assistance à distance d'Echowa, utilisée avec [Echowa Parc](https://github.com/Kasolene/Echowa) : l'agent Echowa l'installe
sur les ordinateurs Windows, et l'équipe informatique prend la main depuis la fiche de l'ordinateur.

Echowa Assist est une version modifiée de **[RustDesk](https://github.com/rustdesk/rustdesk)** (© Purslane Tech Pte. Ltd., licence
**GNU AGPL-3.0**, voir `LICENCE`). Le code d'origine est conservé ; les modifications d'Echowa sont publiées ici, conformément à la licence :

- nom, icônes, logo et couleur d'Echowa (`libs/hbb_common/src/config.rs`, `src/common.rs`, `src/lang.rs`, `src/flutter_ffi.rs`, `res/`, `flutter/`) ;
- `libs/hbb_common` est intégré au dépôt (au lieu d'un sous-module) pour pouvoir y changer le nom ;
- compilation Windows 64 bits par GitHub Actions (`.github/workflows/echowa-assist-windows.yml`), reprise du workflow officiel de RustDesk.

Le README d'origine est conservé dans `README.rustdesk.md`. « RustDesk » est une marque de ses propriétaires ; Echowa Assist n'est ni
approuvé ni soutenu par le projet RustDesk.

## Compiler

Lancer le workflow « Echowa Assist - Windows » (onglet Actions) ou pousser sur la branche `build`. Le programme d'installation
(`Echowa-Assist-windows.exe`) et son empreinte SHA-256 sont publiés dans les « Releases ».
