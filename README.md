# Auron OS

> Build your own custom Linux ISO in 20 minutes. No Cubic pain.

[[License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[[PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[[Stars](https://img.shields.io/github/stars/LordLOLQDH/auron-os?style=social)](https://github.com/LordLOLQDH/auron-os)

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
git clone https://github.com/LordLOLQDH/auron-os
cd auron-os
pip install -r requirements.txt
sudo python main.py
*AppImage/Flatpak:* Kommt mit v0.2

## Quick Start

1. Starte Auron OS
2. Wähle Base: `Linux Mint 22` 
3. Klick Pakete an: `Firefox`, `VSCode`, `Discord`
4. Hit *Build ISO*
5. 20 Min Kaffee holen
6. ISO liegt in `~/AuronOS/builds/`

## Roadmap

Vote mit 👍 in den Issues was als nächstes kommt:

- [ ] *v0.1* Alpha: Mint + Ubuntu Base funktioniert
- [ ] *v0.2* Arch Linux Support https://github.com/LordLOLQDH/auron-os/issues/1
- [ ] *v0.3* Save/Load Build Configs https://github.com/LordLOLQDH/auron-os/issues/2
- [ ] *v0.4* Flatpak Pre-install https://github.com/LordLOLQDH/auron-os/issues/3
- [ ] *v1.0* Stable + GUI polished

Feature fehlt? https://github.com/LordLOLQDH/auron-os/issues/new mit `[Feature]` im Titel.

## Contributing

Auron OS ist Community-driven. Wir brauchen dich.

*Bug gefunden?* → https://github.com/LordLOLQDH/auron-os/issues/new mit Screenshot  
*Code?* → Check https://github.com/LordLOLQDH/auron-os/labels/good%20first%20issue  
*Keine Zeit?* → Gib uns einen ⭐ Star. Hilft beim Algo.

Alle Details: [`CONTRIBUTING.md`](CONTRIBUTING.md)  
Alle Helden: [`CONTRIBUTORS.md`](CONTRIBUTORS.md)

PRs werden in 24h reviewed. Versprochen.

## FAQ

*Q: Warum nicht Cubic nutzen?*  
A: Cubic ist mächtig aber komplex. Auron ist für den 80% Use-Case: "Ich will Mint mit meinen Apps als ISO".

*Q: Welche Distros werden unterstützt?*  
A: Aktuell: Linux Mint 22, Ubuntu 24.04. Arch + Debian kommen wenn genug 👍 da sind.

## Contact

*Bug Reports:* https://github.com/LordLOLQDH/auron-os/issues  
*Mail:* auron@proton.me  
*Maintainer:* https://github.com/LordLOLQDH

## License

GPLv3 © 2026 https://github.com/LordLOLQDH

---

### **Auch die `CONTRIBUTING.md` mit deinem Namen:**

```markdown
# Contributing to Auron OS

Danke dass du Auron OS besser machen willst ❤️ Maintainer: [@LordLOLQDH](https://github.com/LordLOLQDH)

Ziel: Custom Linux ISOs in 20 Min statt 2h.

## Wie du helfen kannst

### 1. Bug melden 🐛
[Issue aufmachen](https://github.com/LordLOLQDH/auron-os/issues/new) mit:

*Problem:* ISO Build crasht bei 87%
*Erwartet:* Build läuft durch
*Schritte:* 1. Mint 22 gewählt 2. Nvidia Treiber angeklickt 3. Build
*Logs/Screenshot:* [hier rein]
*Version:* Auron OS v0.1-alpha

### 2. Feature vorschlagen 💡
[Issue aufmachen](https://github.com/LordLOLQDH/auron-os/issues/new) mit Titel: `[Feature] Arch Linux Support`

Schreib rein: Welches Problem löst es für dich? 
Wir voten mit 👍. Die Top 2 bau ich als nächstes.

### 3. Code beisteuern 🛠️
Easy Einstieg: [`good first issue`](https://github.com/LordLOLQDH/auron-os/labels/good%20first%20issue)

**Setup:**
```bash
git clone https://github.com/LordLOLQDH/auron-os
cd auron-os
pip install -r requirements.txt
python main.py
*Workflow:*
1. Fork → Branch: `git checkout -b fix/nvidia-crash`
2. Coden + Commit
3. PR gegen `main`
4. Ich, LordLOLQDH, reviewe in 24h.

*Code Style:* Lesbar > fancy. `black .` für Python vorm Commit.

## Fragen?
https://github.com/LordLOLQDH/auron-os/discussions oder Mail an auron@proton.me

---

**Checkliste bevor du pushst:**
1. Repo `auron-os` auf github.com/LordLOLQDH erstellen
2. Beide Files rein
3. 5s Demo-Gif mit `peek` aufnehmen und in README verlinken
4. 2 `good first issue` Issues erstellen

**Poste den Repo-Link wenn’s live ist.** Dann bauen wir dir die ersten 3 Issues so, dass Contributors sofort loslegen.
