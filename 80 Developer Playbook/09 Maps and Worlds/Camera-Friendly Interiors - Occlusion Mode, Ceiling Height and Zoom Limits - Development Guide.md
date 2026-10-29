---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Maps/Community Knowledge/Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits.md"
---
# Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits — Development Guide

New practical guidance for [[09 Maps and Worlds/Maps/Community Knowledge/Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits|Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most Roblox games use the default third-person camera, which orbits the character at a distance the player chooses. Interiors built at real-world scale (2.5 m ceilings, 1 m corridors) fight that camera: it snaps against walls, pops through ceilings, or hides the character behind furniture. Players read this as "the game feels janky" without knowing why. The fix is part level design (room proportions) and part...
**Useful source sections:** The two engine settings (Engine API), Which mode suits which map, Room proportions that the default camera tolerates.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Maps/Community Knowledge/Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits|Camera-Friendly Interiors - Occlusion Mode, Ceiling Height and Zoom Limits]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
