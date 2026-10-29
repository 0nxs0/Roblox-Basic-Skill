---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Maps/Community Knowledge/Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance.md"
---
# Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance — Development Guide

New practical guidance for [[09 Maps and Worlds/Maps/Community Knowledge/Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance|Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Landmarks and lighting guide players who are exploring; markers guide players who have a job to do. A quest giver across town, a teammate who needs help, the flag carrier: these need a marker that is visible through walls, shows distance, and turns into an arrow at the screen edge when the target is behind you. Done badly, markers clutter the screen and players stop looking at the world.
**Useful source sections:** In-world marker: BillboardGui, Off-screen arrow: project and clamp, Path lines.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Maps/Community Knowledge/Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance|Map - Objective Markers and Off-Screen Arrows - BillboardGui, Edge Clamping and Distance]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
