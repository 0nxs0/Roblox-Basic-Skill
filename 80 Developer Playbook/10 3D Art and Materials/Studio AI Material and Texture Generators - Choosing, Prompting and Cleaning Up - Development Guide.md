---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Art - Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up.md"
---
# Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Art - Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up|Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox Studio ships two built-in AI tools for surfaces. The Material Generator makes tiling materials (saved as MaterialVariants) from a text phrase. The Texture Generator paints a texture fitted to a specific mesh from a text or image prompt. Both are quick, but used carelessly they produce a map where every surface has a different style, scale and colour temperature. This note is the practical layer on top of...
**Useful source sections:** Which tool?, Prompt patterns that keep a project consistent, Before you generate (Texture Generator).

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Art - Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up|Studio AI Material and Texture Generators - Choosing, Prompting and Cleaning Up]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
