# Auron OS

**Build custom Linux ISOs in 20min. No Cubic pain. No Terminal.**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub issues](https://img.shields.io/github/issues/LordLOLQDH/Auron-OS)](https://github.com/LordLOLQDH/Auron-OS/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> War genervt von Cubic. 15 Klicks, kaputtes Chroot, 2h für eine ISO. 
> 
> Auron OS: Distro wählen → Pakete anklicken → Build. Fertig in 20min.

**Demo:** GIF vom kompletten Build kommt heute Abend.

## Features

- **1-Click Build**: Kein Terminal, kein Chroot-Gefrickel
- **20min statt 2h**: Parallele Downloads + Caching
- **Fail-Safe**: Funktioniert oder gibt klaren Fehler. Kein "irgendwas ist kaputt"
- **Moderne UI**: Python + GTK. Sieht aus wie 2026, nicht 2006
- **Für Einsteiger**: Deine Oma kann damit eine ISO für ihren alten Laptop bauen

## Unterstützte Distros

| Distro | Version | Status |
| --- | --- | --- |
| Linux Mint | 22 "Wilma" | ✅ Stable |
| Ubuntu | 24.04 LTS | ✅ Stable |
| Arch Linux | Rolling | 🔥 Coming next - Vote in #1 |

## Installation

**Nur für Debian/Ubuntu/Mint Hosts:**

```bash
git clone https://github.com/LordLOLQDH/Auron-OS.git
cd Auron-OS
sudo apt install python3-gi python3-gi-cairo gir1.2-gtk-4.0
python3 main.py


*Dependencies:*
- Python 3.10+
- GTK 4.0
- 20GB freier Speicher für ISO-Build

## Usage

1. *Starte Auron OS*: `python3 main.py`
2. *Distro wählen*: Mint oder Ubuntu anklicken
3. *Pakete auswählen*: VSCode, Discord, Spotify, Steam... einfach Haken setzen
4. *Build klicken*: Hol dir einen Kaffee. In 20min ist die ISO fertig
5. *ISO finden*: `~/Auron-OS-Builds/auron-linux-mint-22.iso`

## Roadmap

- Linux Mint + Ubuntu Support
- [ ] Arch Linux Support - Vote in https://github.com/LordLOLQDH/Auron-OS/issues/1
- [ ] Fedora Support
- [ ] Flatpak + AppImage Auto-Install
- [ ] ISO Presets speichern/laden
[x]

*Feature Requests?* Mach ein https://github.com/LordLOLQDH/Auron-OS/issues auf.

## Contributing

Du willst helfen? Mega ❤️

*Für Einsteiger:* Schau dir die https://github.com/LordLOLQDH/Auron-OS/labels/good%20first%20issue Labels an. Dauert 5min. Ich reviewe in 24h.

Mehr Infos: [CONTRIBUTING.md](CONTRIBUTING.md)

## License

This project is licensed under *GPLv3* - see the [LICENSE](LICENSE) file for details.

## Third-party Software & Trademarks

Auron OS does *not* distribute proprietary binaries. 

The tool downloads official, unmodified ISOs directly from `linuxmint.com` and `ubuntu.com`. All additional packages are installed from the official repositories of the respective distribution via `apt` or `flatpak`.

All trademarks, logos, and distro names belong to their respective owners. This project is not affiliated with or endorsed by Canonical Ltd. or the Linux Mint project.

## Röstet mich

Found a bug? Feature fehlt? Bin ich dumm? 

Mach ein https://github.com/LordLOLQDH/Auron-OS/issues auf oder kommentier auf https://www.reddit.com/r/coolgithubprojects/comments/1t3fwot/auron_os_build_custom_linux_isos_in_20min_no/. Ich antworte auf alles.



