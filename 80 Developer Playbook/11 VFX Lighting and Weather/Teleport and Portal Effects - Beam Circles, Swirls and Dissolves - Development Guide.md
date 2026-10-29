---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Teleport and Portal Effects - Beam Circles, Swirls and Dissolves.md"
---
# Teleport and Portal Effects - Beam Circles, Swirls and Dissolves — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Teleport and Portal Effects - Beam Circles, Swirls and Dissolves|Teleport and Portal Effects - Beam Circles, Swirls and Dissolves]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Teleports hide a hard cut (the character jumps across the map, or to another place) behind a short effect. Portals are the same idea made permanent: a doorway that promises "something is on the other side". Both are cheap if built from beams and a few emitters. The DevForum sources include a recreation of the Bloxy Awards teleport swirl built from trails and attachments, and threads where developers suggest beams...
**Useful source sections:** A perfect beam circle (portal rim), Portal interior, Teleport out / in (character).

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Teleport and Portal Effects - Beam Circles, Swirls and Dissolves, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Teleport and Portal Effects - Beam Circles, Swirls and Dissolves and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Teleport and Portal Effects - Beam Circles, Swirls and Dissolves|Teleport and Portal Effects - Beam Circles, Swirls and Dissolves]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
