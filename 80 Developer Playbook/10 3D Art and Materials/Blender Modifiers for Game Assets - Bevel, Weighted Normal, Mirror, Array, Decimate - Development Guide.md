---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate.md"
---
# Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate|Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Modifiers let you keep a model editable (non-destructive) while still exporting clean game geometry. A small, fixed stack covers most Roblox props: Mirror to model half, Array for repeats, Bevel for edges that catch light, Weighted Normal so low-poly shading looks solid, and Decimate when you need a cheaper version fast. The FBX exporter can apply the stack for you on export, so the source file stays flexible....
**Useful source sections:** Recommended order (top to bottom), Mirror, Array.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate|Blender Modifiers for Game Assets - Bevel, Weighted Normal, Mirror, Array, Decimate]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
