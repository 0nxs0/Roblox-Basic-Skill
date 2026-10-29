---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/UV Unwrapping and Texel Density in Studs.md"
---
# UV Unwrapping and Texel Density in Studs — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/UV Unwrapping and Texel Density in Studs|UV Unwrapping and Texel Density in Studs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Texel density is how many texture pixels land on one unit of surface. If a crate has 256 px per stud and the wall behind it has 32, the crate looks razor sharp and the wall looks like mud, even though both textures are "high quality". Keeping density consistent across a scene is what makes Roblox environments look coherent, and it also stops you wasting texture memory on small props.
**Useful source sections:** Roblox's own numbers, Doing the math in Blender, Unwrapping rules that save time.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For UV Unwrapping and Texel Density in Studs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using UV Unwrapping and Texel Density in Studs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/UV Unwrapping and Texel Density in Studs|UV Unwrapping and Texel Density in Studs]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
