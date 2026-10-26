# AutoConvert — téléchargements

Installeurs d'**AutoConvert**, le convertisseur CSV / MAT → MoTeC `.ld` de [JEDAi](https://www.jedai.fr/).
Ce dépôt ne contient que les fichiers d'installation ; le code source n'y est pas.

## ⬇️ [Télécharger la dernière version](https://github.com/JEDAi-engineering/AutoConvert-releases/releases/latest)

| Poste | Fichier |
|---|---|
| Mac Apple silicon (M1 et suivants) | `AutoConvert-<version>-arm64.dmg` |
| Mac Intel | `AutoConvert-<version>-x64.dmg` |
| Windows 10 / 11 (64 bits) | `AutoConvert-Setup-<version>.exe` |

## Installation

- **macOS** : ouvrir le DMG et glisser AutoConvert dans Applications. L'app n'est pas notarisée par Apple : au premier lancement, taper `xattr -cr /Applications/AutoConvert.app` dans le Terminal, ou aller dans Réglages Système › Confidentialité et sécurité › **Ouvrir quand même** (détail dans `LISEZMOI-macOS.txt`, inclus dans le DMG).
- **Windows** : l'installeur n'est pas signé. Sur l'écran SmartScreen, cliquer **Informations complémentaires** › **Exécuter quand même** (voir `LISEZMOI-Windows.txt` dans chaque release).

## Mises à jour automatiques

À partir de la version 1.0.2, AutoConvert vérifie une fois par jour s'il existe une nouvelle version dans ce dépôt. Elle s'installe en un clic (À propos › Mises à jour), après vérification de la signature JEDAi du fichier (Ed25519, `update-manifest.json`).

Chaque release donne le SHA-256 de chaque fichier.

---

© JEDAi. Tous droits réservés.
