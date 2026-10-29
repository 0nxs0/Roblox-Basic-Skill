---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export.md"
---
# Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export|Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Melee weapons are read almost entirely by silhouette: in a Roblox fight the camera is 10-20 studs away and the weapon moves fast. The quickest way to a good-looking low-poly weapon is to design the side profile first as a flat shape, give it thickness, and only then add bevels. This note is the step-by-step modeling order. Grip placement, origin and scale are in Art - Modeling Hand-Held Tools and Weapons -...
**Useful source sections:** Step 0: a profile sketch, Sword (about 150-600 triangles), Axe (about 300-900 triangles).

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export|Melee Weapon Blockout - Sword, Axe and Hammer from Silhouette to Export]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
