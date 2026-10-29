---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal.md"
---
# PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal|PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
For years a Roblox `Decal` was just a flat picture stuck on a face: a puddle decal looked like a painted puddle, a crack looked printed on. The current API reference lists full PBR maps on `Decal` (and therefore on `Texture`, which inherits from Decal): `ColorMap`, `NormalMap`, `RoughnessMap`, `MetalnessMap` and an emissive mask with strength and tint. A decal with any of those extra maps becomes a physically...
**Useful source sections:** What the API reference says (Oct 2026), Detail recipes, Authoring rules.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal|PBR Decals and Textures - Normal, Roughness, Metalness and Emissive Maps on Decal]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
