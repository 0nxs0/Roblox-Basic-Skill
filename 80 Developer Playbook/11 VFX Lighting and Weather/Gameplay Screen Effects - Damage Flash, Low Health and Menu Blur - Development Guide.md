---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur.md"
---
# Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur|Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Post-processing is usually treated as a "make it pretty" lighting setting. In gameplay it is also feedback: a red pulse when you take damage, desaturation near death, blur behind an open shop, a flash for a flashbang. The key Roblox trick is where you parent the effect: effects under the `Camera` show only for that player, while effects under `Lighting` affect everyone's view. This note gives client-only recipes...
**Useful source sections:** Lighting vs Camera, Recipe 1: damage flash, Recipe 2: low health state.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur|Gameplay Screen Effects - Damage Flash, Low Health and Menu Blur]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
