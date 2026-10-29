---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams.md"
---
# Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams|Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A shockwave (a ring of force expanding from an impact) is the effect that says "that hit was heavy". It sells ground slams, landings from great heights, explosions, boss stomps and charged punches. Most of the look comes from one or two meshes scaled up fast and faded out, with particles for texture. DevForum threads in the sources build rings from tweened meshes and from beams with transparency tweens; this note...
**Useful source sections:** Layers (in order of importance), Tween numbers, Materials.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams|Shockwaves - Expanding Mesh Rings, Dust Walls and Ground Slams]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
