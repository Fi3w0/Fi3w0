# Alex — Fi3w0

> Junior DevOps Student · Linux Enthusiast · Terminal-First

---

## About

17-year-old DevOps student — enrolled in a course, but most of what I know came from running real infrastructure, not reading about it.

Maintaining a Docker-based homelab serving my users or me with automated backups and CI/CD pipelines. Docker stacks, Arch Linux as a daily driver, automated backup pipelines, game servers with real users depending on uptime. I've configured networking, tuned performance, and debugged things at 2am because something broke and someone was counting on it being fixed.

I'm not a traditional programmer, but I use AI agents as a deliberate tool: integrating them into workflows, building with them, learning from them — not just prompting for answers. Recently started to code manually with Go and Bash.

**Pronouns:** he/him/sudo  
**Username:** fi3w0 (reads as fi·three·wo)

---

## Infrastructure & Systems

| Area | Tools |
|---|---|
| **OS** | Arch Linux · CachyOS · macOS · Ubuntu Server LTS |
| **Core Skills** | Linux CLI · systemd · Bash scripting |
| **Containers** | Docker · Docker Compose |
| **IaC / Cloud** | Terraform · Ansible · AWS · Azure *(early stages)* |
| **Next Up** | Kubernetes · Networking · Go |

> Terraform, Ansible, AWS, and Azure I'm not so good with them still learning. Linux + Systemd + Docker is where I'm most comfortable.

**Daily Machines**
- MacBook Air M4 — Primary macOS workstation (most used)
- Main PC - Dualbooted Linux/Win11 station for gaming
- ThinkPad T14 Gen 1 — Secondary Linux workstation

Comfortable in any text editor — Nano, Vim, VS Code, Zed, whatever the job needs. Most of my work happens over SSH so CLI tools are most used.

---

## Code & Scripting

Bash and systemd is my go-to for automation. I also write Lua/Luau and Java for game server logic and modding. Started learning Go as secondary lang next to Bash.

```
Go       █████░░░░░░░░░ Intermediate
Bash     ████████░░░░░░ Intermediate
Lua      ███░░░░░░░░░░░ Basic
Java     ██░░░░░░░░░░░░ Basic
```

---

## Projects

### Homelab Infrastructure *(private)*
Production homelab running multiple self-hosted services, fully containerized and managed through Docker Compose with a structured monorepo layout.

**Services**
- Fabric Minecraft server with RCON enabled and a Discord bridge
- Custom Discord bot for general server management
- Dedicated Minecraft RCON bot — kick, ban, pardon, whitelist, broadcasts, and server restarts via slash commands
- Configured Traefik to manage HTTPS routing across multiple services with automatic TLS via Let's Encrypt
- Glances system monitoring dashboard
- Portainer for container management

**CI/CD Pipelines**
- `validate` — Docker Compose syntax check and build on every push
- `deploy` — manual service deployment via workflow dispatch
- `backup` — daily config backup as artifact, release on manual trigger
- `build` — release preparation on version tags

```
Server/
├── discord/
│   ├── discord-bot/
│   └── minecraft-bot/
├── mc/
│   └── fabric-vanilla/
├── proxy/
│   └── traefik/
└── web/
    ├── glances/
    └── portainer/
```

### [Fi3w0-Hyprland](https://github.com/Fi3w0/Fi3w0-Hyprland)
My personal Hyprland dotfiles for Arch Linux on the ThinkPad T14. My main daily environment — configured and maintained for a terminal-first workflow.

---

### [FIW Bosses](https://github.com/Fi3w0/Fiw-Bosses) *(active)*
My most ambitious mod — a full boss framework for Fabric 1.20.1 and NeoForge 1.21.1, inspired by MythicMobs, built from scratch. Define multi-phase bosses entirely through JSON: 42 abilities, phase transitions, custom loot, dialogue systems, custom minions and hot reload. No coding, no restarts — drop a config and it's live. Built primarily with Claude Code.

---

### [FiwStoryMod](https://github.com/Fi3w0/FiwStoryMod)
A Frankenstein mod for my SMP — lore-driven items, custom weapons, and some systems that barely hold together. Held together with borrowed textures and stubbornness. It works, somehow.

---

### Fiw Servers — [fiwservers.lol](https://fiwservers.lol)
Self-hosted Private Minecraft SMP´s for my friends and players, built and maintained end-to-end:
- Custom plugin or mods development
- Automated backup systems
- Discord bot with server management integration
- Custom homepage webpage
- Custom lore and gameplay via plugin/mods or in game mechanics (Not always)

---

## Currently Learning

- Kubernetes cluster management
- Deeper Terraform + Ansible workflows
- Go for automation and CLI tooling
- Networking for better understanding

---

## Languages

Ukrainian · Russian *(both native)* — Spanish *(native-level)* — English *(C1)*

---

## Connect

> Open to collaborative projects, learning opportunities, and anything Linux or infrastructure-related.

- Telegram: @fi3w0  
- Discord: fi3w0  
- GitHub: https://github.com/Fi3w0  
- Website: https://fiwservers.lol

---

[![GitHub](https://img.shields.io/badge/GitHub-Fi3w0-181717?style=flat-square&logo=github)](https://github.com/Fi3w0)
[![Website](https://img.shields.io/badge/Website-fiwservers.lol-000?style=flat-square&logo=google-chrome)](https://fiwservers.lol)

---

<sub>Arch Linux · Docker · SSH · Terminal · Always learning</sub>
