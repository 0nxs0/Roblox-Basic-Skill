---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Lighting/Community Knowledge/Fake Volumetric Light Shafts - Beams and SunRays.md"
---
# Fake Volumetric Light Shafts - Beams and SunRays — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Lighting/Community Knowledge/Fake Volumetric Light Shafts - Beams and SunRays|Fake Volumetric Light Shafts - Beams and SunRays]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Dusty light pouring through a church window, flashlight cones in fog, stage spotlights at a concert: these "volumetric" looks sell atmosphere instantly. Roblox has no true volumetric lighting for local lights, but two tools fake it well. `SunRaysEffect` is a screen-space glow from the sun. For everything else, textured Beams shaped like cones or slabs, with soft edges, read as light in the air. Pair each with a...
**Useful source sections:** SunRaysEffect (sun only), Beam shafts (any light), Dust and motion.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Fake Volumetric Light Shafts - Beams and SunRays, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Fake Volumetric Light Shafts - Beams and SunRays and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Lighting/Community Knowledge/Fake Volumetric Light Shafts - Beams and SunRays|Fake Volumetric Light Shafts - Beams and SunRays]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
