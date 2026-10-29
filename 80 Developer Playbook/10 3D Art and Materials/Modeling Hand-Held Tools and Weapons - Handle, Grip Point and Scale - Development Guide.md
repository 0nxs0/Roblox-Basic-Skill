---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale.md"
---
# Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale|Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A sword, torch or gun that floats beside the hand, points backwards or looks toy-sized is almost always a modeling-side mistake, not a scripting one. The Roblox `Tool` system attaches whatever part is named `Handle` to the character's right hand, then offsets it by `Tool.Grip`. If you build the mesh so that its origin already sits where the palm closes, the grip offset stays near identity and every weapon in your...
**Useful source sections:** How Roblox holds a tool (what the mesh must respect), Blender setup, Scale cheat sheet (game-readable, not real-world).

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale|Modeling Hand-Held Tools and Weapons - Handle, Grip Point and Scale]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
