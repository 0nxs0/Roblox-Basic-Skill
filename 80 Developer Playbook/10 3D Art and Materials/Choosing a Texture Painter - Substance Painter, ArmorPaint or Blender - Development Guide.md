---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender.md"
---
# Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender|Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every Roblox artist eventually asks which program to texture in. The honest answer depends on art style, budget and team size, because Roblox only receives four flat images in the end (Color, Normal, Roughness, Metalness). Any painter that can export those maps works. This note compares the three common choices and what each costs. Export settings are in Texture Export from Blender and Substance for...
**Useful source sections:** The short comparison, Decision guide, Roblox-specific settings for any painter.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender|Choosing a Texture Painter - Substance Painter, ArmorPaint or Blender]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
