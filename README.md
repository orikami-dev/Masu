<p align="center">
  <img src="docs/images/masu-icone.png" width="128" alt="Masu">
</p>

<h1 align="center">Masu</h1>
<p align="center">par ORIKAMI</p>

<p align="center"><i>Bring your own dumped games to Android, with Windows coming soon. A local toolbox to import your keys and game dumps, extract, run and debug native ports, with detailed logs and one-tap crash reports. No game files, keys or source code are published here.</i></p>

<p align="center">
  <a href="https://github.com/orikami-dev/masu/releases/latest">⬇️ <b>Télécharger la dernière version</b></a>
  ·
  <a href="https://github.com/orikami-dev/masu/releases">📦 Toutes les versions</a>
  ·
  <a href="CHANGELOG.md">📝 Journal des versions</a>
</p>

---

## 📦 Le projet

Masu est la boîte à outils qui prépare et lance tes jeux dumpés depuis ta propre console : tu y renseignes tes clés et tes jeux, et Masu rejoue en local tout le processus (extraction, analyse, lancement), avec des journaux détaillés pour déboguer. **Ce dépôt ne publie que les notes de version et l'APK de chaque version.** Il ne contient ni code, ni donnée de jeu, ni clé.

| | |
|---|---|
| 🎮 **Bibliothèque de jeux** | Tes jeux dumpés apparaissent avec leur nom et leur icône ; d'autres jeux seront pris en charge au fil des versions. |
| 🔑 **Tes clés, tes jeux** | Tout reste sur ton appareil, dans le dossier `MASU`. |
| 📤 **Extraction** | Vérification, déchiffrement et extraction de ton dump, avec progression et rapport. |
| 🖼️ **Pilotes Turnip** | Recherche et installation automatiques des pilotes compatibles avec ta puce graphique. |
| 🕹️ **Manettes** | Aides de touches et détection des manettes branchées. |
| 🔄 **Mises à jour** | Dans l'appli, depuis les releases de ce dépôt. |
| 🪟 **Windows** | 🚧 Bientôt (coming soon). Pour l'instant : Android. |

## 🚀 Démarrer (sans PC)

Il te faut : un téléphone ou une tablette **Android 11 ou plus récent**, tes clés (`prod.keys` et `title.keys`) et tes jeux (`.nsp` ou `.xci`), dumpés depuis **ta propre console**. Masu ne fournit ni clé ni jeu, et n'explique pas comment en obtenir.

1. Télécharge `masu-<version>.apk` depuis la [dernière version](https://github.com/orikami-dev/Masu/releases/latest) et ouvre-le. Android te demandera d'autoriser l'installation depuis ton navigateur ou ton gestionnaire de fichiers.
2. Ouvre Masu et touche **Autoriser** : Android affiche « Accès à tous les fichiers », active-le pour Masu. Masu crée alors le dossier `MASU` à la racine du stockage, avec `KEYS`, `GAMES`, `EXTRACTED`, `IMAGES` et `DRIVERS`.
3. Copie tes fichiers sur le téléphone (câble, lecteur de carte microSD USB‑C ou transfert habituel), puis :
   - `prod.keys` et `title.keys` dans `MASU/KEYS` (si Masu les trouve ailleurs, dans Téléchargements par exemple, il propose de les ranger lui-même) ;
   - le jeu dans `MASU/GAMES`, avec sa mise à jour et ses DLC à côté s'il en a.
4. Onglet **Extraction** : touche **Actualiser**, choisis le jeu, puis **Extraire**. Masu vérifie, déchiffre et range le jeu dans `MASU/EXTRACTED/<identifiant de titre>/`, et il apparaît dans la Bibliothèque.

Bon à savoir :

- Les formats compressés `.nsz` et `.xcz` ne sont pas encore pris en charge : décompresse-les d'abord en `.nsp` ou `.xci`.
- Aujourd'hui, Masu **extrait, vérifie et analyse** tes jeux ; aucun jeu ne se lance encore depuis la version publique. Tes retours servent à préparer les prochains.
- Les mises à jour de Masu s'installent ensuite depuis Réglages > Mises à jour.

## ✨ Points forts

- 🧰 Journaux détaillés et rapport de plantage prêt à envoyer, sans jamais de clé dedans.
- 📱 Pensé pour les pliants : plein écran, paysage, pliage sans redémarrage.
- 🎨 Plusieurs thèmes aux couleurs ORIKAMI.
- 🔒 Aucun fichier de jeu ni aucune clé dans ce dépôt.

## 🧪 Tester avec nous

Je ne peux pas tout tester seul : chaque retour aide Masu à reconnaître plus de jeux et plus de téléphones.

- 📋 [Compatibilité des jeux](docs/COMPATIBILITE.md) : ce qui marche, sur quelle puce, avec quelle version.
- ✍️ [Donner un retour](https://github.com/orikami-dev/Masu/issues/new?template=compatibilite.yml) : le bouton « Signaler la compatibilité » de Masu remplit le formulaire pour toi (compte GitHub gratuit requis). Tu relis avant d'envoyer, rien ne part sans toi.
- 🧪 Versions bêta : publiées ici en « préversion » ; Masu les propose si tu actives le canal bêta dans ses réglages.

Seulement avec des jeux que tu possèdes. Ne partage jamais de clé, de fichier de jeu, ni d'information personnelle (nom, nom d'appareil, chemin de dossier).

## ⭐ Mises à jour majeures

| Version | Ce qu'elle a apporté |
|---|---|
| 1.11 ⭐ | Mises à jour et DLC depuis la fiche, téléchargements vérifiés, changer de version, réglages sauvegardés. |
| 1.05 ⭐ | Choix du jeu, mises à jour et DLC, « Vérifier le dump », signalement de compatibilité. |
| 1.00 | Première version publique : pilotes Turnip automatiques, extraction des jeux, aides manette, mises à jour dans l'appli. |

## ⚖️ À savoir

Usage personnel uniquement, avec des jeux que tu possèdes. Aucun fichier de jeu, aucune clé ni aucun code n'est publié dans ce dépôt.

Masu est gratuite. Son code n'est pas publié ; les licences du code tiers qu'elle utilise sont dans l'appli (À propos > Licences).

Non affilié à Nintendo. Les noms et marques cités appartiennent à leurs propriétaires.
