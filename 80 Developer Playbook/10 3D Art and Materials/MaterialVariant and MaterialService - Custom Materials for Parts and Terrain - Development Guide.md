---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/MaterialVariant and MaterialService - Custom Materials for Parts and Terrain.md"
---
# MaterialVariant and MaterialService - Custom Materials for Parts and Terrain — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/MaterialVariant and MaterialService - Custom Materials for Parts and Terrain|MaterialVariant and MaterialService - Custom Materials for Parts and Terrain]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A `MaterialVariant` is a custom tiling PBR material that lives in `MaterialService` and can be applied to any Part, MeshPart or terrain like a built-in material. It is the right tool for big surfaces (floors, walls, roads, cliffs, ground) because it tiles by studs and needs no UV work on Parts. `SurfaceAppearance`, by contrast, is a UV-mapped texture set for one specific mesh. Most good-looking Roblox maps use...
**Useful source sections:** Properties that matter, Setting StudsPerTile from your texture, Applying.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For MaterialVariant and MaterialService - Custom Materials for Parts and Terrain, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using MaterialVariant and MaterialService - Custom Materials for Parts and Terrain and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/MaterialVariant and MaterialService - Custom Materials for Parts and Terrain|MaterialVariant and MaterialService - Custom Materials for Parts and Terrain]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
