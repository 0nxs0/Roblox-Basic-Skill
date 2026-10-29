---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Art - Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules.md"
---
# Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Art - Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules|Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most "this game looks messy" feedback is a colour problem, not a modeling problem: every prop picked its own saturated colour, so nothing reads as important. A small, written palette with rules for value (lightness), saturation and accent use makes free models, AI textures and hand-made props sit together, and it tells players where to look. The technique for applying colours to meshes (atlas vs vertex colours)...
**Useful source sections:** Build the palette in four groups, Rules that keep it working, Applying it in Roblox.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Art - Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules|Colour Palettes for a Consistent Look - Value, Saturation and Accent Rules]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
