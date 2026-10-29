---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Realistic Rock and Cliff Surfaces — PBR Without Waste.md"
---
# Realistic Rock & Cliff Surfaces — PBR Without Waste — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Realistic Rock and Cliff Surfaces — PBR Without Waste|Realistic Rock & Cliff Surfaces — PBR Without Waste]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The realistic cliff reference demonstrates that convincing rock comes from macro shape + normal detail + roughness response + lighting, not just a giant high-resolution color texture.
**Useful source sections:** Asset pipeline, Rock material logic, Tiling control.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Realistic Rock & Cliff Surfaces — PBR Without Waste, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Realistic Rock & Cliff Surfaces — PBR Without Waste and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Realistic Rock and Cliff Surfaces — PBR Without Waste|Realistic Rock & Cliff Surfaces — PBR Without Waste]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
