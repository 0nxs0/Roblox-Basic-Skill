---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Runtime Terrain Destruction and Digging - Craters, FillBall and Replication.md"
---
# Runtime Terrain Destruction and Digging - Craters, FillBall and Replication — Development Guide

New practical guidance for [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Runtime Terrain Destruction and Digging - Craters, FillBall and Replication|Runtime Terrain Destruction and Digging - Craters, FillBall and Replication]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Mining games, artillery games and "dig to the core" experiences change terrain while players are in the server. Terrain edits are authoritative on the server and replicate to every client, so the design questions are: who is allowed to dig, how big each edit is, and how often edits happen. Get those wrong and the game hitches every time a grenade lands.
**Useful source sections:** The building blocks (Engine API), Server-authoritative dig flow, Reading what was dug (mining rewards).

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Runtime Terrain Destruction and Digging - Craters, FillBall and Replication, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Runtime Terrain Destruction and Digging - Craters, FillBall and Replication and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Runtime Terrain Destruction and Digging - Craters, FillBall and Replication|Runtime Terrain Destruction and Digging - Craters, FillBall and Replication]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
