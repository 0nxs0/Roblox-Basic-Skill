---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade.md"
---
# Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade|Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Metal and plastic are the two looks most Roblox props need, and both can be done with no custom textures at all using built-in materials, part `Color` and `Reflectance`. That keeps memory tiny and works on Parts, Unions and MeshParts alike. Knowing what each preset actually contains (which ones have metalness maps, which have no textures) tells you when the built-in look is enough and when to move to a...
**Useful source sections:** What the presets contain (from the Materials reference), Metal recipes, Plastic recipes.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade|Metal and Plastic Looks with Built-in Materials - Presets, Reflectance and When to Upgrade]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
