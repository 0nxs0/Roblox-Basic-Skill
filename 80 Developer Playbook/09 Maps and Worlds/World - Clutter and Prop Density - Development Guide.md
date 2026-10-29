---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Maps/Community Knowledge/World - Clutter and Prop Density.md"
---
# World - Clutter and Prop Density — Development Guide

New practical guidance for [[09 Maps and Worlds/Maps/Community Knowledge/World - Clutter and Prop Density|World - Clutter and Prop Density]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Clutter is what makes a room look lived-in, a street look used, or a ruin look abandoned. Too little and the world feels like a test map; too much and players can't read paths, collide with junk, and phones choke. Treat props in layers with a budget, not as "add more until it looks good".
**Useful source sections:** The three layers, Placement rules, Key kits.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For World - Clutter and Prop Density, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using World - Clutter and Prop Density and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Maps/Community Knowledge/World - Clutter and Prop Density|World - Clutter and Prop Density]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
