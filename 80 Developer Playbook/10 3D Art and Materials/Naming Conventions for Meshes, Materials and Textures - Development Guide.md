---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Naming Conventions for Meshes, Materials and Textures.md"
---
# Naming Conventions for Meshes, Materials and Textures — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Naming Conventions for Meshes, Materials and Textures|Naming Conventions for Meshes, Materials and Textures]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The 3D Importer turns Blender object names into MeshPart names and uses material assignments to decide how a model is split. Textures become separate image assets in the Asset Manager with whatever file name you gave them. After a few hundred assets, "Cube.004" and "Material.012" make a project impossible to search, re-import or hand to another developer. A naming convention costs nothing and makes scripts,...
**Useful source sections:** A simple scheme for Roblox projects, Texture suffixes that match SurfaceAppearance, In Studio.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Naming Conventions for Meshes, Materials and Textures, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Naming Conventions for Meshes, Materials and Textures and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Naming Conventions for Meshes, Materials and Textures|Naming Conventions for Meshes, Materials and Textures]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
