---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Geometry Nodes Scatter and Kitbash - Realize Instances Before Export.md"
---
# Geometry Nodes Scatter and Kitbash - Realize Instances Before Export — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Geometry Nodes Scatter and Kitbash - Realize Instances Before Export|Geometry Nodes Scatter and Kitbash - Realize Instances Before Export]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Geometry Nodes in Blender can scatter pebbles over a cliff, grow bolts along a pipe, or assemble a building from kit pieces in seconds. The catch for Roblox: what you see in the viewport is mostly instances, and instances do not survive a normal FBX export the way you expect. Forum reports and the FBX exporter notes agree that instancing is not preserved; the reliable path is a Realize Instances node, then apply...
**Useful source sections:** Basic scatter graph, Kitbash use, Bake it, or place it in Studio?.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Geometry Nodes Scatter and Kitbash - Realize Instances Before Export, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Geometry Nodes Scatter and Kitbash - Realize Instances Before Export and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Geometry Nodes Scatter and Kitbash - Realize Instances Before Export|Geometry Nodes Scatter and Kitbash - Realize Instances Before Export]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
