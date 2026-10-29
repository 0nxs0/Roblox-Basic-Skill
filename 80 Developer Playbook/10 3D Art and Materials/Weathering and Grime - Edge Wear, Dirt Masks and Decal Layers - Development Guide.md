---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers.md"
---
# Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers|Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Clean assets look like toys; weathered assets look like they belong to a place and a story. Weathering is also how you make 20 copies of the same crate stop looking identical. On Roblox there are two layers to work with: wear baked into the asset's textures (edge wear, dirt in crevices, rust streaks) and decals placed in the level (stains, cracks, leaks, posters) that vary each copy for almost no cost. This note...
**Useful source sections:** Where wear really happens (paint the logic, not noise), Baked wear in Blender (no paid tools), Decal layers in the level.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers|Weathering and Grime - Edge Wear, Dirt Masks and Decal Layers]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
