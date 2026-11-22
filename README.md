<div align="center">

<img src="https://www.quorum-au.workers.dev/files/Logo.png" alt="Quorum" width="150" />

# Quorum

**An Among Us utility that runs the lobby.**

Roles, host tools, vent control and a packet spy in one overlay. One DLL,
loaded through BepInEx, updated on launch.

[Website](https://www.quorum-au.workers.dev) · [Releases](https://github.com/quorum-au/quorum/releases/latest) · [Issues](https://github.com/quorum-au/quorum/issues)

</div>

---

> [!CAUTION]
> The only official place to download Quorum is this repository and
> **[quorum-au.workers.dev](https://www.quorum-au.workers.dev)**. Any other site
> offering a build is not affiliated with us and should not be trusted.
>
> By downloading, keeping or running this software you agree to the
> [License](https://github.com/quorum-au/quorum/blob/main/LICENSE).

> [!NOTE]
> Quorum is intended for **educational, experimental and personal use only**.
> It is a **utility** for *Among Us*, powered by **BepInEx**, that lets players
> change gameplay, unlock features and experiment with the game's mechanics
> through a feature-rich menu.
>
> Bans are a real consequence of using it online. Read the disclaimer at the
> bottom before you load into a lobby you care about.

---

## Install

1. Install **BepInEx 6** (IL2CPP, x64) into your Among Us folder.
2. Drop `Quorum.dll` into `BepInEx/plugins/`.
3. Launch the game once, then press **Del** in a lobby.

Settings live in `BepInEx/config/Quorum.cfg`. The menu updates itself on launch;
the SHA-256 on the site is the file the site is serving, so you can check what
you have.

## What's in it

| area | what it does |
|---|---|
| **Sight** | ESP, tracers with distance, radar, zoom, full bright, see ghosts, roles and disguises |
| **Wire** | packet capture, replay codes, task and game-state logs, host response time |
| **Authority** | host tools, role control, doors, sabotages, vents, voting and eject |
| **Warden** | cheat detection, behaviour scoring and automatic removal |
| **Pressure** | RPC flooding and spam tooling, rate-limited so it does not hang the lobby |
| **Cover** | spoofer, cosmetics unlock, chat mimic, incognito |

## Contributing

Open an issue first, and prefix the title so it can be triaged:

| prefix | use |
|---|---|
| `[BUG REPORT]` | something is broken — include the log line and the game version |
| `[SUGGESTION]` | a feature or a change you want considered |
| `[PULL REQUEST]` | you have code ready and want it reviewed |

Send the pull request after the issue exists. If it lands you get credited,
unless you would rather not be named.

## Disclaimer

- Not affiliated with Among Us or Innersloth LLC. Nothing here is endorsed or
  sponsored by Innersloth.
- Portions of the materials contained herein are the property of Innersloth LLC.
- Using this mod can violate the terms of service of Among Us, which may lead to
  punitive action, including temporary or permanent bans from the game.
- The founders are not responsible for any consequences you may face from using
  it. Use at your own risk.

---

<div align="center">

[![License](https://img.shields.io/github/license/quorum-au/quorum?style=flat-square&color=c8102e)](https://github.com/quorum-au/quorum/blob/main/LICENSE)
[![Builds](https://img.shields.io/github/actions/workflow/status/quorum-au/quorum/ci-release.yml?branch=main&style=flat-square&label=builds&color=c8102e)](https://github.com/quorum-au/quorum/actions)
[![Downloads](https://img.shields.io/github/downloads/quorum-au/quorum/latest/total?style=flat-square&color=c8102e)](https://github.com/quorum-au/quorum/releases/latest)
[![Latest](https://img.shields.io/github/v/release/quorum-au/quorum?style=flat-square&color=c8102e)](https://github.com/quorum-au/quorum/releases/latest)
[![Stars](https://img.shields.io/github/stars/quorum-au/quorum?style=flat-square&color=c8102e)](https://github.com/quorum-au/quorum/stargazers)

### Founding members

Three people who would rather not be named.

</div>
