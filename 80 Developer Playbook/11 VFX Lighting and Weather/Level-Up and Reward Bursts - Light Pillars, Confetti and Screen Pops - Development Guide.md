---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops.md"
---
# Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops|Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The moment a player levels up, opens a chest or unlocks a rare item is the biggest emotional beat in many Roblox games, and it is often shown with a plain text popup. A short, layered reward burst (in the world for other players to see, on screen for the player) makes progress feel earned and advertises it to everyone nearby. The key is a tiered system: common rewards get a small pop, rare ones get the full show,...
**Useful source sections:** The four layers, World pillar, Burst particles.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops|Level-Up and Reward Bursts - Light Pillars, Confetti and Screen Pops]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
