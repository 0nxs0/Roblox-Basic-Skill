---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Weather/Community Knowledge/GlobalWind - Grass, Clouds, Particles and Gusts.md"
---
# GlobalWind - Grass, Clouds, Particles and Gusts — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Weather/Community Knowledge/GlobalWind - Grass, Clouds, Particles and Gusts|GlobalWind - Grass, Clouds, Particles and Gusts]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Wind ties a weather system together: rain slants, smoke drifts the same way the grass bends, clouds move, and a storm visibly picks up. Roblox has one engine-level value for this, `Workspace.GlobalWind`, released in late 2023 ("Breeze into Wind!" announcement). Terrain grass and dynamic clouds follow it automatically; particles follow it when you opt in. Setting it from one weather owner keeps every system...
**Useful source sections:** What responds, Particles that follow wind, Strength guide (starting points).

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For GlobalWind - Grass, Clouds, Particles and Gusts, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using GlobalWind - Grass, Clouds, Particles and Gusts and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Weather/Community Knowledge/GlobalWind - Grass, Clouds, Particles and Gusts|GlobalWind - Grass, Clouds, Particles and Gusts]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
