# 📝 Changelog

Studio: ORIKAMI.

## 1.16

- Per-game apps: with an engine app installed, Masu builds and installs an app for an extracted game, right on the phone (signing key created on the device).
- Extraction: the game list unfolds inside its frame instead of a small floating menu.

## 1.15

- English interface: Masu follows the phone's language (French or English); screens, messages, log and crash reports are translated.
- Game updates with your own GitHub token in Settings › Game updates.
- Easier-to-spot list of games to extract; game page shows the game version and the APK version.
- "Report compatibility" now sends the result in English.

## 1.11 ⭐

- Updates and DLC installed from the game page, shown under their game in the Extraction screen.
- Drop-down list to choose the game to extract; version, size and status of games on the covers.
- "Report" button on the page of unsupported games.
- Downloads verified by SHA-256 fingerprint, versions validated and pinned, "Change version".
- Settings saved automatically.
- Update and DLC files are no longer mistaken for games to extract.

## 1.05 ⭐

- Choice of the game to extract when several copies are in GAMES, NSP as well as XCI.
- Games without a module are still extracted, with their name and icon.
- Game engine detection, "Verify the dump" and module analysis during extraction.
- Update and DLC placed next to the game are taken into account during extraction.
- "Report compatibility" from a game page, "Receive beta versions" setting, graphics capabilities report.
- "Prepare the game" translates shaders in advance; the extracted game is read directly from MASU.
- The detected engine is kept after a restart.

## 1.00

- Turnip drivers found and installed automatically according to the graphics chip.
- Game extraction (NSP, XCI) to `MASU/EXTRACTED/<id>/`, with progress, cancellation and a report.
- Button hints and Controllers section shown only when a controller is connected.
- "Custom" profile expanded in place; system bars matched to the theme.
- In-app updates from this repository's releases.
