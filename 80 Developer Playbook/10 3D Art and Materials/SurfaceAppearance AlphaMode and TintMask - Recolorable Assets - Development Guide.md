---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/SurfaceAppearance AlphaMode and TintMask - Recolorable Assets.md"
---
# SurfaceAppearance AlphaMode and TintMask - Recolorable Assets — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/SurfaceAppearance AlphaMode and TintMask - Recolorable Assets|SurfaceAppearance AlphaMode and TintMask - Recolorable Assets]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`SurfaceAppearance.AlphaMode` decides what the alpha channel of the `ColorMap` means. Picking the right mode is how you get see-through foliage and fences, colour-customizable cars and skins, and paint that shows the part colour underneath. The `TintMask` mode plus the `SurfaceAppearance.Color` property (a long-requested feature on the DevForum) lets you ship one texture set and recolour it per team, per player...
**Useful source sections:** The four modes, Transparency mode: two behaviours, TintMask recipe (recolourable car paint).

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For SurfaceAppearance AlphaMode and TintMask - Recolorable Assets, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using SurfaceAppearance AlphaMode and TintMask - Recolorable Assets and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/SurfaceAppearance AlphaMode and TintMask - Recolorable Assets|SurfaceAppearance AlphaMode and TintMask - Recolorable Assets]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
