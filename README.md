# Pax Autocratica Trainer — Mod Menu & Cheats for PC (v1.0.0)

**Pax Autocratica trainer** with an in-game **mod menu** covering both halves of the game: god mode and one-hit kill for the FPS expeditions, infinite resources and instant build for the colony, max loyalty and no rebellion for your citizens, plus core control for the roguelite loop. Works with the **Steam** and **Epic Games Store** Early Access builds of Multiverse's totalitarian colony sim. Open the overlay with `Insert`, flip a toggle, keep ruling.

[![Version](https://img.shields.io/badge/version-v1.0.0-b4442f)](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-1c1813)](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases/latest)
[![Stores](https://img.shields.io/badge/stores-Steam%20%7C%20Epic-1b2838)](#compatibility)
[![Early Access](https://img.shields.io/badge/game-Early%20Access-d99a2b)](#early-access-and-broken-offsets)
[![Downloads](https://img.shields.io/github/downloads/YOUR-USERNAME/pax-autocratica-trainer/total)](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases)
[![License](https://img.shields.io/badge/license-MIT-e0c17a)](LICENSE)

> **[⬇ Download the latest Pax Autocratica trainer](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases/latest)**

---

## Contents

- [What this is](#what-this-is)
- [Early Access and broken offsets](#early-access-and-broken-offsets)
- [Compatibility](#compatibility)
- [Features](#features)
  - [Leader](#leader--player-cheats) · [Squad](#squad--troop-cheats) · [Cores](#cores--roguelite-progression) · [Colony](#colony--base-building-cheats) · [Citizens](#citizens--loyalty-and-control) · [Expedition](#expedition--run-cheats) · [Camera](#camera--accessibility-options) · [Trainer](#trainer-options)
- [Hotkeys](#hotkeys)
- [Installation](#installation)
- [How to use the mod menu](#how-to-use-the-mod-menu)
- [Troubleshooting](#troubleshooting)
- [FAQ](#faq)
- [Changelog](#changelog)
- [Disclaimer](#disclaimer)

---

## What this is

*Pax Autocratica* is two games bolted together. Half of it is a colony sim where you assign citizens to mine, haul, research and manufacture, and shape them through propaganda, surveillance, comfort or fear until they're loyal — or until dissent turns into revolt. The other half is a first-person roguelite where you drop into the Tyris System with a squad, fight through bullet-hell battlefields of infantry, tanks and mechs, collect Cores that reshape your build, and drag weakened enemies home to the prison to be converted.

A trainer for it has to cover both. Colony cheats are about skipping the grind — infinite resources, instant build, instant research. Expedition cheats are about surviving a bullet-hell roguelite that does not care about your feelings. And the citizen system sits in the middle, which is where the most interesting options live: freeze loyalty, suppress rebellion, make every conversion succeed.

Single-player game, no PvP, no anti-cheat. Nothing here touches anyone else.

---

## Early Access and broken offsets

Read this before you file an issue.

Pax Autocratica launched into Early Access on 10 August 2026, and the developers expect to stay there for roughly two years. That means frequent patches. Every patch can move the memory addresses this trainer writes to, which is why a trainer that worked yesterday can silently stop working today.

**What that means in practice:**

- Each release here lists the exact game build it was verified against. Check that first.
- If your game auto-updated and options stopped responding, that's the cause. Not your install.
- Options fail independently. Infinite resources can keep working while god mode goes dead.
- Turn on **Read-only mode** in the Trainer tab to check whether the trainer is still reading correct values before you write anything.

If you want to avoid the churn entirely, Steam lets you pin a specific build: right-click the game → Properties → Betas → and select a previous branch if the developers publish one. Otherwise, expect a lag of a few days between a game patch and a matching trainer build.

The developers have also said **co-op is a feature they hope to add during Early Access**. It isn't in the game today, and everything in this trainer assumes single-player. If co-op ships, treat every world-state option as something that would affect your partner, and check for an updated release before using it in a shared session.

---

## Compatibility

| | |
|---|---|
| **Game** | Pax Autocratica (Multiverse, Early Access since 10 August 2026) |
| **Stores** | Steam · Epic Games Store |
| **Game version** | Early Access launch build and later patches — see [release notes](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases) |
| **OS** | Windows 10 and Windows 11, 64-bit |
| **Runtime** | .NET Desktop Runtime 8 or newer, DirectX 11 |
| **Also known as** | The game was previously developed under the name *Earth From Another Sun* — old saves and old builds are not supported |
| **Demo build** | Not supported, the demo uses a separate app ID |
| **Steam Deck / Proton** | Not supported |
| **Consoles** | No console release |

---

## Features

50+ options across eight tabs. Sliders show the shipped default; ranges are listed where they matter.

### Leader — player cheats

| Option | What it does | Hotkey |
|---|---|---|
| **God mode** | Bullets, lasers, artillery and drones all ignored | `F1` |
| **Infinite stamina** | Sprint and dodge without a meter | `F2` |
| **Infinite ammo** | Magazines never empty | `F3` |
| **No reload** | Skip the animation entirely | — |
| **Damage multiplier** | `1x`–`100x`, default `5x` | — |
| **No recoil or spread** | Every shot lands where you aimed | — |
| **Movement speed** | `1x`–`10x`, default `2x` | — |
| **Revive on death** | Get back up instead of ending the run | `F4` |

**Revive on death** is the one that changes the roguelite maths. A failed expedition normally costs you the run and everything on it; with this on, a bad Core roll stops being a death sentence.

### Squad — troop cheats

| Option | What it does | Hotkey |
|---|---|---|
| **Troops are invulnerable** | Your soldiers stop dying on you | `F5` |
| **Squad damage multiplier** | `1x`–`50x`, default `3x` | — |
| **Squad size** | `1`–`24`, default `8` | — |
| **Instant troop respawn** | Fallen soldiers rejoin immediately | — |
| **Unlock all soldier types** | Every unit available from the start | — |
| **Troops never break** | No panic, no rout, no desertion | — |
| **Squad fire rate** | `1x`–`10x`, default `1x` | — |

The game openly invites you to use your own troops as expendable shields. **Troops are invulnerable** takes that option away and gives you a real army instead, which is a very different playstyle.

### Cores — roguelite progression

| Option | What it does | Hotkey |
|---|---|---|
| **Core drop rate** | `1x`–`20x`, default `3x` | — |
| **Always max rarity** | Every Core drops at the top tier | — |
| **Free rerolls** | Reroll a Core offer without cost | — |
| **Core slots** | `3`–`12`, default `6` | — |
| **Keep Cores between runs** | Carry your build out of the expedition | — |
| **Combination Cores always trigger** | Synergies fire regardless of the set | — |
| **Unlock all Weapon Cores** | The full catalogue, immediately | — |

**Keep Cores between runs** is the single biggest change to how the game plays. It turns a roguelite into a straight progression game. Fun once, and worth knowing that it removes most of the tension the loop is built on.

### Colony — base building cheats

| Option | What it does | Hotkey |
|---|---|---|
| **Infinite resources** | Ore, food, components, everything | `F6` |
| **Instant build** | Structures finish the moment they're placed | — |
| **Instant research** | No tech timers | — |
| **Instant manufacturing** | Weapons, armour and supplies come off the line at once | — |
| **No power drain** | Grid never browns out | — |
| **Free placement** | Ignore terrain and adjacency restrictions | — |
| **Resource multiplier** | `1x`–`50x`, default `5x` | — |
| **Population cap** | `10`–`500`, default `120` | — |

### Citizens — loyalty and control

| Option | What it does | Hotkey |
|---|---|---|
| **Freeze loyalty at maximum** | Nobody ever wavers | `F7` |
| **No dissent or rebellion** | Revolt never triggers | — |
| **Citizens never tire** | No sleep, hunger or morale drain | — |
| **Propaganda effectiveness** | `1x`–`20x`, default `1x` | — |
| **Surveillance range** | `10`–`500 m`, default `80 m` | — |
| **Instant indoctrination** | Prison conversion completes immediately | — |
| **Conversion always succeeds** | Every captured enemy becomes a citizen | — |
| **No feuds** | Citizens stop forming grudges with each other | — |

This is the most Pax Autocratica–specific tab, and the one worth thinking about before you use. The citizen simulation — fear against comfort, loyalty against quiet resentment, the moment dissent tips into revolt — is the actual point of the game, and its satire only lands if the system can push back at you. Freezing loyalty at maximum removes the entire argument the game is making. Worth seeing once, worth turning off after.

### Expedition — run cheats

| Option | What it does | Hotkey |
|---|---|---|
| **One-hit kill** | Anything short of a boss drops instantly | `F8` |
| **Freeze enemy AI** | They spawn, they never engage | `F9` |
| **Incoming damage** | `0%`–`100%`, default `0%` | — |
| **Sector Overlord health** | `1%`–`100%`, default `100%` | — |
| **Instant capture** | Weakened enemies go down without the struggle | — |
| **Reveal the sector map** | Uncover the whole territory at once | — |
| **Loot and merchant highlight** | Outline pickups and traders within `20`–`400 m`, default `150 m` | — |
| **Return to colony** | Extract from anywhere | `F10` |

**Sector Overlord health** is deliberately a slider rather than a toggle. Dropping a boss to `25%` keeps the bullet-hell patterns intact and just shortens the fight, which is usually what people actually want.

### Camera & accessibility options

| Option | What it does | Hotkey |
|---|---|---|
| **Field of view** | `60`–`140 deg`, default `90 deg` | — |
| **Free camera** | Detach it from the Leader | `F11` |
| **Hide interface** | Drop the HUD and all prompts | `F12` |
| **Reduce flashing effects** | Damp muzzle flash, explosions and strobing | — |
| **Reduce projectile glare** | Tone down bullet-hell bloom | — |
| **Disable screen shake** | — | — |
| **Disable fog and haze** | Full draw distance | — |
| **Extended photo mode** | Filters, depth of field, timescale | — |

Steam flags this game for flashing lights and photosensitive epilepsy. **Reduce flashing effects**, **Reduce projectile glare** and **Disable screen shake** exist for that reason and are the options most worth having even if you never touch anything else in this trainer. They are not a medical safeguard — if you are photosensitive, treat the game's own warning as the one that counts.

### Trainer options

| Option | What it does | Hotkey |
|---|---|---|
| **Hotkeys** | Global bindings on or off | — |
| **Menu key** | Rebind the overlay — `Insert`, `F1`, `Home`, `~` | — |
| **Overlay opacity** | `40%`–`100%`, default `92%` | — |
| **Read-only mode** | Show values, write nothing — use this after a game patch | — |
| **Back up saves before writing** | Copy the save folder on first attach | — |
| **Reset all on run end** | Turn everything off when an expedition finishes | — |
| **Auto-load profile** | Apply the saved set on launch | — |

---

## Hotkeys

| Key | Action |
|---|---|
| `Insert` | Open or close the mod menu |
| `F1` | God mode |
| `F2` | Infinite stamina |
| `F3` | Infinite ammo |
| `F4` | Revive on death |
| `F5` | Troops are invulnerable |
| `F6` | Infinite resources |
| `F7` | Freeze loyalty at maximum |
| `F8` | One-hit kill |
| `F9` | Freeze enemy AI |
| `F10` | Return to colony |
| `F11` | Free camera |
| `F12` | Hide interface |
| `End` | Reset every option |
| `↑ ↓ ← → Enter` | Navigate the menu without a mouse |

---

## Installation

1. **Download** the latest archive from the [Releases page](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases/latest).
2. **Unblock it** — right-click the `.zip`, choose Properties, tick *Unblock*, then Apply. Windows quarantines downloaded archives and the trainer won't attach otherwise.
3. **Extract** anywhere outside `Program Files`.
4. **Launch the game first** and load a colony, so the process exists.
5. **Run the trainer as administrator.** The header should read `attached` in green.
6. **Press `Insert`.**

Back up your saves before the first run. The game uses Steam Cloud, so a corrupted local save can sync upward — disable Cloud for the game while you experiment if you care about your colony.

```
%USERPROFILE%\AppData\LocalLow\Multiverse\Pax Autocratica
```

---

## How to use the mod menu

Pick a tab on the left, flip what you need on the right. Sliders update live.

A few setups worth knowing:

- **Colony first:** `Infinite resources` + `Instant build` + `Instant research`. Skip straight to the late-game base and see the systems that only open up at scale.
- **Learning bullet hell:** `Incoming damage 0%` + `Revive on death`, with everything else stock. You still have to read the patterns; you just stop losing the run to them.
- **Boss practice:** `Sector Overlord health 25%` + `Freeze enemy AI` off. Shortens the fight without removing it.
- **Testing Core builds:** `Core drop rate 20x` + `Always max rarity` + `Free rerolls` + `Keep Cores between runs`.
- **Screenshots:** `Hide interface` + `Free camera` + `Reduce projectile glare`.
- **Photosensitivity:** `Reduce flashing effects` + `Reduce projectile glare` + `Disable screen shake`, and nothing else.

---

## Troubleshooting

**Options stopped working after a game update.** This is the Early Access tax. See [Early Access and broken offsets](#early-access-and-broken-offsets). Check the Releases page for a build matching your game version.

**Trainer says the process wasn't found.** The game has to be running and past the main menu. Launch Pax Autocratica, load a colony, then start the trainer. If you're on Epic, launch through the Epic client rather than the executable directly.

**Nothing happens when I press Insert.** Another overlay is eating the key. Steam's overlay, Discord and RTSS are the usual suspects. Rebind under **Trainer → Menu key**.

**Colony cheats work but expedition cheats don't.** Expedition memory is allocated when a run starts. Attach the trainer, drop into an expedition, then toggle. Some options won't bind until you're actually in a sector.

**My colony broke after using population cap or free placement.** Those two write persistent structural data. Restore the backup the trainer made on first attach, or roll back through Steam Cloud.

**Windows Defender flagged it.** Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Add an exclusion if you're comfortable with that — and if you'd rather not, don't. That's a reasonable call.

**I own the demo, not the game.** The demo is a separate app ID and isn't supported.

---

## FAQ

### Does the Pax Autocratica trainer work with the latest Early Access patch?

Check the Releases page — each build lists the game version it was verified against. The game is in Early Access and patches frequently, so expect a short gap between a game update and a matching trainer build.

### Will I get banned for using cheats in Pax Autocratica?

It's a single-player game with no anti-cheat and no multiplayer, so there's nothing to be banned from. Steam achievements generally still unlock, since they're awarded locally.

### Does it work on the Epic Games Store version?

Yes. Launch through the Epic client so the process starts with the right environment.

### Is this the same game as Earth From Another Sun?

Pax Autocratica grew out of that project and was renamed. This trainer targets the current Early Access builds only — old Earth From Another Sun builds and saves aren't supported.

### Does it work on Steam Deck or Linux?

No. Windows only. Proton changes how the game's memory is laid out.

### Can it help with the flashing lights?

There are three options for it in the Camera tab: reduce flashing effects, reduce projectile glare, and disable screen shake. They damp the effect, they don't eliminate it. If you're photosensitive, take the game's own warning seriously rather than relying on a third-party tool.

### Will it corrupt my colony save?

Options that write persistent data — population cap, free placement, unlock all soldier types, keep Cores between runs — can leave your save in a state the game didn't expect. That's why the trainer backs up on first attach and why it's worth turning off Steam Cloud while you experiment.

### Does it have infinite resources?

Yes, in the Colony tab, along with instant build, instant research and instant manufacturing.

### How do I turn everything off?

Press `End`.

---

## Changelog

### v1.0.0 — 11 August 2026

First public release, one day after the game's Early Access launch. 50+ options across Leader, Squad, Cores, Colony, Citizens, Expedition, Camera and Trainer. Read-only mode and automatic save backup included from the start, because Early Access.

Full history on the [Releases page](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/releases).

---

## Contributing

Bug reports welcome — open an [issue](https://github.com/YOUR-USERNAME/pax-autocratica-trainer/issues) with your **exact game build number**, store (Steam or Epic), Windows version, whether you were in the colony or on an expedition, and which option misbehaved. Build number matters more than anything else here.

---

## Disclaimer

Unofficial fan tool. **Not affiliated with, endorsed by, or connected to Multiverse, Valve or Epic Games.** *Pax Autocratica* and all related names and assets belong to their respective owners.

Intended for single-player use on your own copy. Modifying a running game's memory carries real risk of crashes and save corruption, and more so in an Early Access build that changes weekly — back up your saves, and use it at your own risk.

Released under the [MIT License](LICENSE).

---

<sub>Pax Autocratica trainer · Pax Autocratica mod menu · Pax Autocratica cheats for PC · god mode, infinite resources, instant build, infinite ammo, one-hit kill, max loyalty, unlimited Cores · Steam and Epic Games Store · Multiverse · colony sim and FPS roguelite · formerly Earth From Another Sun</sub>
