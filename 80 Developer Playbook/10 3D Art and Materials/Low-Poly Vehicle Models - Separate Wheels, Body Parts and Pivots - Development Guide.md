---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots.md"
---
# Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots|Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A car mesh exported as one lump cannot spin its wheels, open its doors or show glass. Roblox vehicles are built from constraints (hinges, springs, cylindrical constraints) between separate parts, so the model has to arrive already split into the pieces those constraints need, each with a sensible pivot. Getting the split right in Blender saves hours of re-exporting later. Chassis tuning lives in the Vehicles...
**Useful source sections:** The split (one object per moving or special piece), Wheel rules, Body rules.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots|Low-Poly Vehicle Models - Separate Wheels, Body Parts and Pivots]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
