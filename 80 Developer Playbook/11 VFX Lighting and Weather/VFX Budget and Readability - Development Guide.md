---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/VFX Budget and Readability.md"
---
# VFX Budget and Readability — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/VFX Budget and Readability|VFX Budget and Readability]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every VFX should answer: - What gameplay fact does the effect communicate? - Can the player read it at gameplay camera distance? - How many can exist simultaneously? - What happens on low graphics/mobile?
**Useful source sections:** Layer order, Distance policy, Global caps.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For VFX Budget and Readability, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using VFX Budget and Readability and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/VFX Budget and Readability|VFX Budget and Readability]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
