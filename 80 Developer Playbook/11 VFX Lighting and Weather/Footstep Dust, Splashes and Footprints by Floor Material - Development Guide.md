---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Footstep Dust, Splashes and Footprints by Floor Material.md"
---
# Footstep Dust, Splashes and Footprints by Floor Material — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Footstep Dust, Splashes and Footprints by Floor Material|Footstep Dust, Splashes and Footprints by Floor Material]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Small puffs at the feet are what make a character feel grounded in the world: dust on dirt, spray in puddles, flakes in snow, nothing on carpet. The vault's audio note covers material-based footstep sounds; this is the visual half. It reuses the same trigger (a `Footstep` animation marker) and the same lookup (`Humanoid.FloorMaterial`), as DevForum threads in the sources suggest, and adds landing puffs and...
**Useful source sections:** Trigger, Material table, Water and puddles.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Footstep Dust, Splashes and Footprints by Floor Material, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Footstep Dust, Splashes and Footprints by Floor Material and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Footstep Dust, Splashes and Footprints by Floor Material|Footstep Dust, Splashes and Footprints by Floor Material]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
