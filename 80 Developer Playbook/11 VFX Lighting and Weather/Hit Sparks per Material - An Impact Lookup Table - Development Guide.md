---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Hit Sparks per Material - An Impact Lookup Table.md"
---
# Hit Sparks per Material - An Impact Lookup Table — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Hit Sparks per Material - An Impact Lookup Table|Hit Sparks per Material - An Impact Lookup Table]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A bullet that throws orange sparks off wood, or dust off a metal door, breaks immersion instantly. Per-material impacts are a small table plus one function: every raycast hit already tells you the `Material`, the `Position` and the surface `Normal`, so the right effect costs nothing extra to choose. This note gives a ready-to-use grouping of Roblox materials and a tuned effect for each group.
**Useful source sections:** Step 1: group materials, Step 2: one effect per family, Step 3: one pooled emitter per family.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Hit Sparks per Material - An Impact Lookup Table, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Hit Sparks per Material - An Impact Lookup Table and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Hit Sparks per Material - An Impact Lookup Table|Hit Sparks per Material - An Impact Lookup Table]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
