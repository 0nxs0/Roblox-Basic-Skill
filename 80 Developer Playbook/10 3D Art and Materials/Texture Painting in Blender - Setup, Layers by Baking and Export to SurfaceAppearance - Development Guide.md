---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance.md"
---
# Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance|Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
You do not need a paid painter to texture Roblox props. Blender's Texture Paint mode paints directly on the 3D model, and Roblox's own accessory tutorials use it. Its weakness is that it has no real layer stack, so the trick is to build layers with bakes and multiple images, then combine them. This note is the practical setup for game props and accessories. For exporting the finished maps, see Texture Export from...
**Useful source sections:** 1. Prepare the mesh, 2. Create the images, 3. Paint mode setup.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance|Texture Painting in Blender - Setup, Layers by Baking and Export to SurfaceAppearance]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
