# Alex — Fi3w0

> 🌙 just a guy who loves Linux, building things, and occasionally breaking them

**OS & Systems**

![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Ubuntu Server](https://img.shields.io/badge/Ubuntu_Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![CachyOS](https://img.shields.io/badge/CachyOS-0A0E14?style=for-the-badge&logo=archlinux&logoColor=00BCD4)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Learning / Exploring**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Languages & Scripting**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)

**Editors**

![Zed](https://img.shields.io/badge/Zed-084CCF?style=for-the-badge&logo=zedindustries&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Nano](https://img.shields.io/badge/GNU_Nano-336791?style=for-the-badge&logo=gnu&logoColor=white)

---
![Homelab and dev setup: Arch + Hyprland on T14, Ubuntu Server homelab with Docker stacks](banner.png)
---

## 👋 About

Hi, I'm Fiw, just a guy who loves tech and building whatever comes to mind, so I do a little of everything I find interesting or just want to try out. One day it's a Minecraft mod, the next it's a whole desktop shell or some homelab service I probably didn't need but built anyway.

My main thing is Linux and the systems that run the software I build or deploy: Docker, Traefik, backups, CI/CD, a mini PC under my desk quietly keeping my friends' servers alive. That's the part I actually care about, the stuff holding everything up that nobody notices when it works.

So I'm not a coder, and I'm not really trying to be one, at least not right now. I think in systems more than in code. I write Bash, Go, Lua and a bit of Java by hand, and for anything heavier I lean on AI agents while keeping the design and direction mine.

**Pronouns:** he/him/sudo    
**Username:** fi3w0 (reads as fi·three·wo)

---

## ⚙️ Infrastructure & Systems

| Area | Tools |
|---|---|
| **OS** | Arch Linux · CachyOS · macOS · Ubuntu Server LTS |
| **Core** | Linux CLI · systemd · Bash scripting · networking |
| **Containers** | Docker · Docker Compose · Portainer |
| **Routing** | Traefik · auto TLS · self-hosted services |
| **CI/CD** | GitHub Actions (validate · deploy · backup · build) |

Linux, systemd, Docker, and Bash are where I'm at home. Kubernetes, Terraform, and Ansible are on the list, I've touched them and I'll come back properly.

**Daily Machines**
- MacBook Air M4, my main macOS workstation (most used)
- Main PC, dual-booted Linux / Win11 for gaming and heavy loads
- ThinkPad T14 Gen 1, secondary Linux box running Arch + Hyprland

Most of my work happens over SSH, so CLI tools get the most mileage. Comfortable in whatever editor the job needs.

---

## 💻 Code & Scripting

What I write by hand vs. what I architect and direct.

```
By hand
  Bash   ████████░░░░░  comfortable
  Go     ██████░░░░░░░  learning, CLI tooling
  Lua    █████░░░░░░░░  game logic, configs
  Java   ███░░░░░░░░░░  read & modify

Architect & direct (AI-assisted)
  Kotlin · TypeScript · Python · QML
  I own the design, libraries, and how it fits together.
  The implementation gets done under my direction.
```

---

## 🛠️ Projects

### [Moonlit Shell](https://github.com/Fi3w0/Moonlit-shell)
A handcrafted Arch Linux desktop built on Hyprland and a custom Quickshell (QML / Qt6) interface. My daily driver on the ThinkPad T14, rebuilt from the ground up after my old Waybar setup kept hitting walls.

Twelve real panels (WiFi connect, Bluetooth pairing, clipboard history, audio/MPRIS hub, system monitor, wallpaper carousel), frosted glass throughout, one coherent Catppuccin Mocha theme across everything, and an automated installer with Minimal / Developer / Full presets. The bar reads stats straight from `/proc` and `sysfs`, no external daemon.

---

### [FIW Bosses](https://github.com/Fi3w0/Fiw-Bosses) *(active)*
My most ambitious mod. A data-driven boss framework for NeoForge 1.21.1 and Fabric, inspired by MythicMobs, built from scratch. Define fully custom multi-phase bosses entirely through JSON: 42 abilities, phase transitions, custom minions, dialogue systems, custom loot, hot reload. No coding, no restarts, drop a config and run `/boss reload`. On Modrinth.

---

### [FIW Tools](https://github.com/Fi3w0/Fiw-Tools) *(active)*
The sibling mod to Fiw Bosses. A data-driven custom-item framework, also JSON-only and fully server-side, so vanilla clients connect with no install. Define items, weapons, and armor on top of vanilla data components, with 8 player-balanced abilities. With both mods installed, bosses can drop or wear Fiw Tools items by id. On Modrinth.

---

### Skyxern — [fiwservers.lol](https://fiwservers.lol)
Self-hosted private Minecraft SMPs for my friends and players, built and maintained end-to-end:
- Custom mods and plugins
- Automated backup systems
- Discord bots for server management and RCON control
- A custom community website and a self-hosted homelab dashboard
- Custom lore, items, and gameplay where it makes sense

> Runs behind Traefik on the homelab: Fabric / NeoForge servers, Python + discord.py bots, a FastAPI + React community site, and a Bun/TypeScript dashboard.

---

## 🔭 Currently

- Finishing my DevOps course
- Coming back to Kubernetes, Terraform, and Ansible when there's time
- Go for automation and CLI tooling
- Getting better at networking

---

<details>
<summary><b>🎭 What I call myself</b></summary>

<br>

I wear a few hats, and honestly they all overlap:

- **DevOps** — Docker, CI/CD, reverse proxies, automation, keeping things running
- **Systems / Platform Engineer** — this is the core. I design how the whole thing fits together and build the platform my software runs on
- **Systems Architect** — I think in systems first. I own the design and the decisions, then build it myself or direct an AI agent to
- **Builder / Dev** — at the end of the day I just make stuff: mods, desktops, bots, services, whatever I feel like

Not a job title, just how I actually work.

</details>

---

## 🌍 Languages

Ukrainian · Russian *(both native)* — Spanish *(native-level)* — English *(C1)*

---

## 📫 Connect

> Open to collaborative projects, learning, and anything Linux or infrastructure related.

- Telegram: @fi3w0
- Discord: fi3w0
- GitHub: https://github.com/Fi3w0

---

[![GitHub](https://img.shields.io/badge/GitHub-Fi3w0-cba6f7?style=flat-square&logo=github)](https://github.com/Fi3w0)
[![Website](https://img.shields.io/badge/Website-fiwservers.lol-89b4fa?style=flat-square&logo=google-chrome)](https://fiwservers.lol)

---

<sub>Arch Linux · Docker · SSH · Terminal · Always learning</sub>
