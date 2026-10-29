---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits.md"
---
# Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits|Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Hats, helmets, backpacks and wings are the most common reward items in Roblox games, and the same mesh can be both an in-game cosmetic and (later) a Marketplace item. If you model it to the Marketplace rules from day one, you never have to rebuild it. The rules are strict: one mesh, at most 4,000 triangles, watertight, and inside a size box that depends on the item type and body scale. This note is the modeling...
**Useful source sections:** The numbers to model against (Normal / Rthro body scale), Blender recipe: a beanie-style hat, Blender recipe: a backpack.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits|Rigid Hats and Backpacks - Blender Recipe to UGC Size Limits]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
