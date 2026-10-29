---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Glowing Surfaces - Neon Material, Emissive Masks and Bloom.md"
---
# Glowing Surfaces - Neon Material, Emissive Masks and Bloom — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Glowing Surfaces - Neon Material, Emissive Masks and Bloom|Glowing Surfaces - Neon Material, Emissive Masks and Bloom]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Glowing screens, sci-fi panels, lava cracks, magic runes and car lights all need surfaces that look self-lit. On Roblox you have three tools: the built-in Neon material (whole part glows), emissive maps on `SurfaceAppearance`, `MaterialVariant` and now `Decal` (only masked pixels glow), and lights that actually illuminate the surroundings. Mixing them correctly gives a convincing glow at low cost.
**Useful source sections:** Tool 1: Neon material, Tool 2: emissive masks, Tool 3: real lights.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Glowing Surfaces - Neon Material, Emissive Masks and Bloom, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Glowing Surfaces - Neon Material, Emissive Masks and Bloom and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Glowing Surfaces - Neon Material, Emissive Masks and Bloom|Glowing Surfaces - Neon Material, Emissive Masks and Bloom]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
