---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Parts, Unions or MeshParts - Choosing the Geometry Type.md"
---
# Parts, Unions or MeshParts - Choosing the Geometry Type — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Parts, Unions or MeshParts - Choosing the Geometry Type|Parts, Unions or MeshParts - Choosing the Geometry Type]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox gives you three ways to make shapes: primitive Parts (blocks, wedges, cylinders, spheres), solid modeling results (Union, Intersect, Negate, stored as `PartOperation` instances), and imported MeshParts. Builders argue about this endlessly; the practical answer depends on what the object is and how many copies exist. This note gives a decision table and the hidden costs of each.
**Useful source sections:** Quick comparison, Decision guide, Hidden costs to know.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Parts, Unions or MeshParts - Choosing the Geometry Type, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Parts, Unions or MeshParts - Choosing the Geometry Type and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Parts, Unions or MeshParts - Choosing the Geometry Type|Parts, Unions or MeshParts - Choosing the Geometry Type]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
