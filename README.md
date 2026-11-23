# Lucas de Menezes Cavalcante

**Computer Engineer · Poli-USP (Polytechnic School of the University of São Paulo)**

I'm a computer engineer who has worked across most of the stack: Linux kernel drivers and firmware security research at LARC-USP, data pipelines that power live websites, desktop and Android apps, and a co-op game shipped on Steam. I like seeing an issue I can solve, then following through with it, from start to finish.

I'm open to software engineering roles across firmware, backend, data and systems work.
 
## Apps & games
 
**[Tears of Vanfell](https://store.steampowered.com/app/3184640/)**
A co-op roguelite I co-developed and shipped on Steam: gameplay systems, multiplayer synchronization and persistent progression.
`Unity` `C#`
 
**[Team Trials Score Tracker](https://github.com/LucasTyph/TeamTrialsScoreTracker)**
A Windows app that reads game results from screenshots with OCR and shows, from averages over every match, which teams and characters raise or lower your score.
`Python` `PySide6` `Tesseract OCR` `pandas`
 
**[Volume Widget](https://github.com/LucasTyph/VolumeWidget)**
A slim, customizable Android home-screen widget for controlling volume, with no dependencies and no always-on background service.
`Java` `Android`

## Data & web
 
**[Steam Tag Analysis](https://github.com/LucasTyph/SteamTagAnalysis)** · [live site](https://lucastyph.github.io/SteamTagAnalysis/)
Which genre mixes beat expectations on Steam, and how does a game's reception change after launch? A resumable scraper for ~200k apps, a statistical model of 60k games and 120M reviews, and a website that runs SQL in the browser with no backend. Data refreshes every month on its own.
`Python` `DuckDB` `scikit-learn` `React` `TypeScript` `GitHub Actions`
 
**[Prédio a Prédio](https://github.com/LucasTyph/predio-a-predio)** · [live site](https://lucastyph.github.io/predio-a-predio/)
The sale history of every residential building in São Paulo since 2005, built from public tax records, placed on the map and adjusted for inflation. The map loads only the area you're looking at, so the whole city runs from static files.
`Python` `pandas` `Shapely` `MapLibre` `PMTiles`
 
**[Chess Openings Trainer](https://github.com/LucasTyph/ChessOpeningsTrainerV2)** · [try it](https://lucastyph.github.io/ChessOpeningsTrainerV2/)
Learn an opening repertoire with Anki-style spaced repetition. PGN import, opening names, and a finder for lines you haven't prepared. The whole app is one HTML file that works offline.
`JavaScript` `chess.js` `esbuild`

## Systems & security
 
**[TOTP + SPDM Device Attestation](https://github.com/LucasTyph/TOTP-SPDM-buildroot-module)**
Research at LARC-USP: a Linux kernel USB driver that authenticates a device with the DMTF SPDM standard, then keeps re-checking it with time-based codes. The device side runs both in QEMU and as a USB gadget.
`C` `Linux kernel` `QEMU` `Buildroot` `libspdm`
 
**[File Integrity Monitoring](https://github.com/LucasTyph/FileIntegrityMonitoring)**
Watches a directory in real time and reports files added, changed or deleted against a SHA-256 baseline.
`Python` `watchdog`
