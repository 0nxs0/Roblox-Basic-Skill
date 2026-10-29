---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/Muzzle Flash Recipe - Flash, Light, Smoke and Shell.md"
---
# Muzzle Flash Recipe - Flash, Light, Smoke and Shell — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/Muzzle Flash Recipe - Flash, Light, Smoke and Shell|Muzzle Flash Recipe - Flash, Light, Smoke and Shell]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A gun without a good muzzle flash feels like a toy, and a gun with a bad one (a big orange square that lingers) feels worse. A convincing flash is four tiny layers that together last under a tenth of a second: a bright star-shaped flash, a one-frame light pulse on nearby walls, a puff of smoke that hangs a moment, and an ejected shell. Everything is client-side and pooled, because automatic weapons fire 10+ times...
**Useful source sections:** Rig, Starting values, Firing code (client).

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Muzzle Flash Recipe - Flash, Light, Smoke and Shell, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Muzzle Flash Recipe - Flash, Light, Smoke and Shell and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/Muzzle Flash Recipe - Flash, Light, Smoke and Shell|Muzzle Flash Recipe - Flash, Light, Smoke and Shell]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
