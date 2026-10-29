---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values.md"
---
# Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values|Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Normal maps are the most common reason a PBR asset "looks wrong" after import: bumps look like dents, lighting looks inside-out, or the map seems to do nothing at all. Roblox's API reference spells out exactly what it expects, so these problems are fixable in minutes once you know the rules.
**Useful source sections:** What Roblox expects, Symptom table, Quick visual test (no tools needed).

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values|Normal Map Rules for Roblox - OpenGL Green, Tangents and Flat Values]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
