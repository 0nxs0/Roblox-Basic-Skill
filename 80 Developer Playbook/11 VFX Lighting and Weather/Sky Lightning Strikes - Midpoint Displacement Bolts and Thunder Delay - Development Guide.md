---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Weather/Community Knowledge/Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay.md"
---
# Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Weather/Community Knowledge/Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay|Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A storm needs lightning that looks different every time, lights up the world for a split second, and is followed by thunder that arrives later the farther away it struck. Pre-made bolt meshes repeat quickly. A procedural bolt from midpoint displacement (the same recursive idea used for fractal terrain, as Krazydad and several game-dev write-ups describe) gives endless variation with a few lines of code, and you...
**Useful source sections:** The algorithm, Rendering the bolt, Timing of a strike (about 0.5 s total).

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Weather/Community Knowledge/Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay|Sky Lightning Strikes - Midpoint Displacement Bolts and Thunder Delay]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
