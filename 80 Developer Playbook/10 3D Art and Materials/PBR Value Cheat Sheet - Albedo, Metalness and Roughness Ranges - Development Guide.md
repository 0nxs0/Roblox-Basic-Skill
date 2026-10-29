---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges.md"
---
# PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges|PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
PBR only looks right when the numbers in your maps are plausible. Under Roblox's Future lighting, an albedo painted pure black looks like a hole, pure white glows like neon, and a metalness map full of greys looks like plastic covered in dust. These ranges come from Adobe's widely used PBR Guide and the open Physically Based database; they apply directly to `SurfaceAppearance` and `MaterialVariant` maps, which...
**Useful source sections:** Albedo (ColorMap) for non-metals, Metals, Roughness.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges|PBR Value Cheat Sheet - Albedo, Metalness and Roughness Ranges]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
