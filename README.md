# DS-AdminMode

An **admin / cheat menu** for [Data Center](https://store.steampowered.com/app/2261080/Data_Center/) — free store purchases, free XP shop unlocks, unlimited reputation, and add-any-amount buttons for money, XP, and reputation.

## Features

- Press **F6** in game for a draggable admin window. While open, the cursor is freed and game input is muted so clicks and typing don't leak into the game.
- **Free store purchases** — anything charged through the game's money system (shop checkout, hiring, walls, blueprint pastes) costs nothing. Income still works normally.
- **Free XP unlocks** — locked shop items unlock regardless of your XP. Unlocks are the game's own and stay unlocked permanently, even after removing the mod.
- **Unlimited reputation** — pins reputation at a configurable value and blocks reputation loss. Toggling off restores your real value.
- **Add money / XP / reputation** — type an amount or use quick buttons (+$10k/+$100k/+$1M, +100/+1k/+10k XP, +10/+50/+100 rep). All adds go through the game's own systems so the HUD, sounds, and side effects run normally.
- Toggle states persist across sessions, and current money/XP/rep show live in the menu.

## Install

1. Install [MelonLoader](https://github.com/LavaGang/MelonLoader) into Data Center.
2. Download `DS-AdminMode_v*.dll` from [Releases](../../releases) and drop it into the game's `Mods` folder.

## Config

`UserData\DS-AdminMode.cfg`, section `[DSAdminMode]`: `MenuKey` (F6), `FreePurchases`, `FreeXpUnlocks`, `UnlimitedReputation`, `UnlimitedReputationValue` (1000), `VerboseLog`, plus remembered menu values/position.

## Caveats

- Saving while **unlimited reputation is ON** writes the pinned value into the save — toggle it off first if you want to keep your real value.
- Free purchases applies to every money charge in the game, not just the shop.
- Co-op is untested — use solo or as host only.

---

*Part of the DS- mod family by Tyler Sander:*
[DS-Core](https://github.com/TylerSander/DS-Core) · [DS-Calculator](https://github.com/TylerSander/DS-Calculator) · [DS-QSFP](https://github.com/TylerSander/DS-QSFP) · [DS-Hotbar](https://github.com/TylerSander/DS-Hotbar) · [DS-AdminMode](https://github.com/TylerSander/DS-AdminMode)
