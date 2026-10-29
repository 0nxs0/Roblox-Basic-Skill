---
kind: development-companion
category: "16 Fast Game Kit"
source-note: "16 Fast Game Kit/Starter Code/Starter Code - 09 Settings and SoundGroups.md"
---
# Starter Code - 09 Settings and SoundGroups — Development Guide

New practical guidance for [[16 Fast Game Kit/Starter Code/Starter Code - 09 Settings and SoundGroups|Starter Code - 09 Settings and SoundGroups]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
1. `default.project.json` creates two `SoundGroup`s in `SoundService`: `Music` (0.5) and `SFX` (0.8). 2. Every `Sound` in the game sets its `SoundGroup` property to one of them. Parenting a Sound under a SoundGroup does not assign it; the property does (official `SoundGroup` docs). 3. `SettingsPanel` changes `SoundGroup.Volume` on the client. Property changes made on a client stay on that client, so each player...
**Useful source sections:** Why this matters, How it works, The code.

## Apply it
Use this topic as part of **assemble small loops from understood parts**.
- **Define the contract:** For Starter Code - 09 Settings and SoundGroups, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Build one playable loop, separate configuration from behavior, and document replacement points.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check dependencies, licenses, authority, and lifecycle before reuse.

## Validate before shipping
- **Expected path:** Build one small feature using Starter Code - 09 Settings and SoundGroups and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Run in a clean place and swap one component safely.

## Connected work
- Source note: [[16 Fast Game Kit/Starter Code/Starter Code - 09 Settings and SoundGroups|Starter Code - 09 Settings and SoundGroups]]
- Category hub: [[80 Developer Playbook/16 Fast Game Kit/_Development Hub|16 Fast Game Kit development hub]]
