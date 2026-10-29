---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs.md"
---
# Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs|Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A glowing circle of runes on the ground is the clearest way to say "a spell is being cast here", and it doubles as a gameplay telegraph: the circle shows exactly where an attack will land and how long until it does. Paid aura packs sell spinning sigils, but the effect is simple to build yourself from flat parts, decals and beams. This note covers the build, the animation and how to make the circle an honest warning.
**Useful source sections:** Build: layered flat rings, Animation (one client loop), Rising beams and pillars.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs|Magic Circles - Rotating Rune Decals, Rising Beams and Cast Telegraphs]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
