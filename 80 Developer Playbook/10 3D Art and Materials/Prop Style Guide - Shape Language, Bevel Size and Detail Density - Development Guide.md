---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Prop Style Guide - Shape Language, Bevel Size and Detail Density.md"
---
# Prop Style Guide - Shape Language, Bevel Size and Detail Density — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Prop Style Guide - Shape Language, Bevel Size and Detail Density|Prop Style Guide - Shape Language, Bevel Size and Detail Density]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
When three people (or one person plus an AI generator) make props, the map quickly looks like an asset flip: one barrel is chunky and cartoon, the next is sharp and photoreal. A one-page prop style guide fixes this by writing down the few numbers that define your look. It is not a mood board; it is a set of rules an artist can check a model against in two minutes. Overall art direction is in Stylized vs Realistic...
**Useful source sections:** 1. Shape language (one line each), 2. Edge treatment (the most visible rule), 3. Detail density.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Prop Style Guide - Shape Language, Bevel Size and Detail Density, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Prop Style Guide - Shape Language, Bevel Size and Detail Density and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Prop Style Guide - Shape Language, Bevel Size and Detail Density|Prop Style Guide - Shape Language, Bevel Size and Detail Density]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
