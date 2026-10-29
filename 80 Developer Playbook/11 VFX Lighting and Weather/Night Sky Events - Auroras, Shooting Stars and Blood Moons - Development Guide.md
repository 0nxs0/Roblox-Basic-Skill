---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Night Sky Events - Auroras, Shooting Stars and Blood Moons.md"
---
# Night Sky Events - Auroras, Shooting Stars and Blood Moons — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Night Sky Events - Auroras, Shooting Stars and Blood Moons|Night Sky Events - Auroras, Shooting Stars and Blood Moons]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Night is when many Roblox maps go dull: a dark skybox, some stars, done. Rare sky events (an aurora over the snowfields, a meteor shower, a red "blood moon" that buffs monsters) give players a reason to stay online after dark and to screenshot. They are mostly built from Beams and Trails placed far away and kept relative to the camera, plus small `Sky` and post-processing changes.
**Useful source sections:** Rule 1: sky effects follow the camera, Aurora curtains (Beams), Shooting stars and meteor showers.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Night Sky Events - Auroras, Shooting Stars and Blood Moons, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Night Sky Events - Auroras, Shooting Stars and Blood Moons and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Night Sky Events - Auroras, Shooting Stars and Blood Moons|Night Sky Events - Auroras, Shooting Stars and Blood Moons]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
