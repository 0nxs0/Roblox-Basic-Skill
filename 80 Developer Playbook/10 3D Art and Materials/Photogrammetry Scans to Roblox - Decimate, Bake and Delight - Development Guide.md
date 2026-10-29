---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Photogrammetry Scans to Roblox - Decimate, Bake and Delight.md"
---
# Photogrammetry Scans to Roblox - Decimate, Bake and Delight — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Photogrammetry Scans to Roblox - Decimate, Bake and Delight|Photogrammetry Scans to Roblox - Decimate, Bake and Delight]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Photogrammetry turns many photos of a real object (a rock, a tree stump, a statue you own, a pile of bricks) into a textured 3D model. It is the fastest way to get believable realistic props, but raw scans are unusable in Roblox: millions of triangles, messy UVs, 8K textures and baked-in sunlight. The job is to transfer the scan's detail onto a light game mesh. This is the same high-to-low workflow as sculpting,...
**Useful source sections:** Capture tools (licences checked Oct 2026), Shooting tips (short), Cleanup in Blender.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Photogrammetry Scans to Roblox - Decimate, Bake and Delight, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Photogrammetry Scans to Roblox - Decimate, Bake and Delight and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Photogrammetry Scans to Roblox - Decimate, Bake and Delight|Photogrammetry Scans to Roblox - Decimate, Bake and Delight]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
