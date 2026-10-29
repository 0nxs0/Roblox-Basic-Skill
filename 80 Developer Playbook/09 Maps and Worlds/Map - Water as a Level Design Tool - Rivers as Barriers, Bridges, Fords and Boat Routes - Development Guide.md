---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes.md"
---
# Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes — Development Guide

New practical guidance for [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes|Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Water is the most natural way to shape movement on a terrain map. A river says "go around" without an invisible wall, a bridge says "cross here", and a lake opens long sightlines. The existing water notes cover how terrain water works (swim checks, settings, shorelines). This one is about what water does to the layout: where people cross, where they fight, and how fast they move.
**Useful source sections:** What water changes, Crossings are the design, Rivers as boundaries.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes|Map - Water as a Level Design Tool - Rivers as Barriers, Bridges, Fords and Boat Routes]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
