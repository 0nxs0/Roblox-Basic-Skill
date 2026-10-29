---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes.md"
---
# Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes|Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Sculpts, photogrammetry scans and AI-generated models (Tripo, Rodin, Studio's own generators) come out as millions of uneven triangles. Roblox caps a single mesh at 20,000 triangles, and anything that deforms (characters, creatures, cloth) needs edge loops in the right places. Retopology means building a new, light mesh on top of the dense one, then baking the detail back as textures. It is slower than Decimate...
**Useful source sections:** Decide first: retopo, remesh or decimate?, Blender's built-in tools, Free external option.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes|Retopology Basics - Turning Sculpts and AI Meshes into Game Meshes]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
