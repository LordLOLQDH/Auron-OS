# Auron OS

> Build your own custom Linux ISO in 20 minutes. No Cubic pain.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/LordLOLQDH/Auron-OS?style=social)](https://github.com/LordLOLQDH/Auron-OS)

**Auron OS** ist ein 1-Click ISO Builder. Du wählst deine Distro, klickst Pakete an, drückst Build. Fertig. 

Kein Terminal. Kein Cubic-Tutorial für 2h. Kein kaputtes Chroot.

**[Demo GIF hier einfügen]** 
<!-- Nimm `peek` auf: sudo apt install peek → 5s vom Klick bis "ISO fertig" -->

## Warum Auron OS?

| | Cubic | Auron OS |
| --- | --- | --- |
| **Setup** | 15 Klicks + Chroot | 1 Klick |
| **Zeit** | 2h für erste ISO | 20 Min |
| **Fehler** | "Chroot broken" Horror | Geht oder klarer Fehler |
| **Zielgruppe** | Linux Profis | Jeder der Mint installieren kann |

## Install

**Alpha Warnung:** Noch nicht für Produktion. Teste in einer VM.

```bash
git clone https://github.com/LordLOLQDH/Auron-OS
cd Auron-OS
pip install -r requirements.txt
sudo python main.py
_AppImage/Flatpak:_ Kommt mit v0.2

## Quick Start

1. Starte Auron OS
2. Wähle Base: `Linux Mint 22` 
3. Klick Pakete an: `Firefox`, `VSCode`, `Discord`
4. Hit _Build ISO_
5. 20 Min Kaffee holen
6. ISO liegt in `~/AuronOS/builds/`

## Roadmap

Vote mit 👍 in den Issues was als nächstes kommt:

- [ ] _v0.1_ Alpha: Mint + Ubuntu Base funktioniert
- [ ] _v0.2_ Arch Linux Support https://github.com/LordLOLQDH/Auron-OS/issues/1
- [ ] _v0.3_ Save/Load Build Configs https://github.com/LordLOLQDH/Auron-OS/issues/2
- [ ] _v0.4_ Flatpak Pre-install https://github.com/LordLOLQDH/Auron-OS/issues/3
- [ ] _v1.0_ Stable + GUI polished

Feature fehlt? https://github.com/LordLOLQDH/Auron-OS/issues/new mit `[Feature]` im Titel.

## Contributing

Auron OS ist Community-driven. Wir brauchen dich.

_Bug gefunden?_ → https://github.com/LordLOLQDH/Auron-OS/issues/new mit Screenshot  
_Code?_ → Check https://github.com/LordLOLQDH/Auron-OS/labels/good%20first%20issue  
_Keine Zeit?_ → Gib uns einen ⭐ Star. Hilft beim Algo.

Alle Details: [`CONTRIBUTING.md`](CONTRIBUTING.md)  
Alle Helden: [`CONTRIBUTORS.md`](CONTRIBUTORS.md)

PRs werden in 24h reviewed. Versprochen.

## FAQ

_Q: Warum nicht Cubic nutzen?_  
A: Cubic ist mächtig aber komplex. Auron ist für den 80% Use-Case: "Ich will Mint mit meinen Apps als ISO".

_Q: Welche Distros werden unterstützt?_  
A: Aktuell: Linux Mint 22, Ubuntu 24.04. Arch + Debian kommen wenn genug 👍 da sind.

## Contact

_Bug Reports:_ https://github.com/LordLOLQDH/Auron-OS/issues  
_Mail:_ auron@proton.me  
_Maintainer:_ https://github.com/LordLOLQDH

## License

GPLv3 © 2026 https://github.com/LordLOLQDH
