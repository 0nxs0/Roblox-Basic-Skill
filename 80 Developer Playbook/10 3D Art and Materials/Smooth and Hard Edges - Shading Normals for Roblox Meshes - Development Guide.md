---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Smooth and Hard Edges - Shading Normals for Roblox Meshes.md"
---
# Smooth and Hard Edges - Shading Normals for Roblox Meshes — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Smooth and Hard Edges - Shading Normals for Roblox Meshes|Smooth and Hard Edges - Shading Normals for Roblox Meshes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A low-poly mesh looks either clean and crafted or lumpy and "AI-generated" mostly because of its vertex normals, not its triangle count. Normals tell the renderer which way each vertex faces; smooth normals blend lighting across faces, split (hard) normals make a crisp edge. Roblox imports whatever normals your FBX/glTF carries, so the shading you see in Blender's Solid view is close to what Studio shows. Getting...
**Useful source sections:** The three looks, The rule that prevents black smears, Export and import.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Smooth and Hard Edges - Shading Normals for Roblox Meshes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Smooth and Hard Edges - Shading Normals for Roblox Meshes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Smooth and Hard Edges - Shading Normals for Roblox Meshes|Smooth and Hard Edges - Shading Normals for Roblox Meshes]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
