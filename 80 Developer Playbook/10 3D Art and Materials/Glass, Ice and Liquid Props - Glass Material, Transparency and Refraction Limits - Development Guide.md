---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits.md"
---
# Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits|Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Windows, bottles, potion flasks, fish tanks, ice blocks and crystal pickups all need "see-through" surfaces, and they are some of the most common art bugs in Roblox: windows that turn invisible, potions whose liquid disappears behind the glass, and frame-rate drops from stacked transparency. Roblox gives you three tools: the built-in Glass material, plain `Transparency` on any material, and `SurfaceAppearance`...
**Useful source sections:** Glass material facts, Choosing the right approach, Modeling tips.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits|Glass, Ice and Liquid Props - Glass Material, Transparency and Refraction Limits]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
