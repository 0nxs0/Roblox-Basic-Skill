---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Weather/Community Knowledge/FX - Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift.md"
---
# Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Weather/Community Knowledge/FX - Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift|Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Weather that only changes the sky is decoration. Weather that changes how the game plays (cars slide in the rain, snipers lose range in fog, storms cover your footsteps from guards, wind bends arrows) creates stories and makes players react to the forecast. The risk is unfairness: a gameplay modifier the player cannot see is a bug from their point of view. The rule for this whole note: every gameplay effect must...
**Useful source sections:** Architecture, Wet grip (vehicles and surfaces), Visibility.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Weather/Community Knowledge/FX - Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift|Weather That Changes Gameplay - Wet Grip, Visibility, Hearing and Wind Drift]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
