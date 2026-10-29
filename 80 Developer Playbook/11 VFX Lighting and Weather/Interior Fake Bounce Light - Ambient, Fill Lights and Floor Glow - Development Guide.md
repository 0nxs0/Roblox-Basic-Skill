---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow.md"
---
# Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow|Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In real rooms, sunlight hits the floor and bounces onto walls and the ceiling, so nothing indoors is truly black. Roblox's lighting gives you sky-occluded areas lit by `Lighting.Ambient` plus whatever local lights you place, but no full multi-bounce lighting you can art-direct per room. Rooms therefore often look either pitch black or flat grey. Lighting artists in every engine solve this the same way: fake the...
**Useful source sections:** Step 1: get the global ambient right, Step 2: the three fake bounce lights, Step 3: key lights with shadows.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow|Interior Fake Bounce Light - Ambient, Fill Lights and Floor Glow]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
