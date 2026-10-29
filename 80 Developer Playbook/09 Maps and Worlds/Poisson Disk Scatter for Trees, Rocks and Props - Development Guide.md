---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Poisson Disk Scatter for Trees, Rocks and Props.md"
---
# Poisson Disk Scatter for Trees, Rocks and Props — Development Guide

New practical guidance for [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Poisson Disk Scatter for Trees, Rocks and Props|Poisson Disk Scatter for Trees, Rocks and Props]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Random scatter (`math.random` X and Z per tree) produces clumps and bald patches, and trees end up intersecting. Grid scatter looks planted. Poisson disk sampling gives "natural but even" spacing: every point is at least `r` studs from every other point, with no visible pattern. It is the standard method for forests, rock fields, flower patches and enemy spawn points, and Robert Bridson's 2007 algorithm makes it...
**Useful source sections:** How Bridson's algorithm works, Luau implementation (2D, X/Z plane), From points to a forest.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Poisson Disk Scatter for Trees, Rocks and Props, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Poisson Disk Scatter for Trees, Rocks and Props and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Poisson Disk Scatter for Trees, Rocks and Props|Poisson Disk Scatter for Trees, Rocks and Props]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
