---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw.md"
---
# Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw|Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Trees are where Roblox maps most often lose frame rate and look cheap at the same time. Two approaches work: solid blob canopies (no transparency, cheapest, very "toy" look) and leaf cards (flat planes with a leaf-cluster texture whose alpha cuts out the shape). Cards look far richer but bring three problems: back faces disappear, lighting on the back looks wrong, and transparent pixels cost fill rate (overdraw)....
**Useful source sections:** Option 1: solid canopy (fastest), Option 2: leaf cards, Performance settings in Studio.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw|Stylized Trees and Foliage Cards - Alpha Cutouts, Two-Sided Leaves and Overdraw]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
