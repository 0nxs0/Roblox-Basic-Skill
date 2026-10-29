---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR.md"
---
# Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR|Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The hand-painted look (think classic fantasy MMOs and many popular Roblox adventure games) puts the lighting into the colour texture: painted highlights on top edges, darker crevices, soft colour gradients. It looks rich on cheap low-poly meshes and holds up on phones because it does not depend on the device's lighting quality. The catch: Roblox's lighting is physically based, so you must stop the engine from...
**Useful source sections:** What to paint into the colour map, Keep painted light and engine light from clashing, Material settings: "flat PBR".

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Community Knowledge/Model - Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR|Hand-Painted Texture Style on Roblox - Baked Light, Edge Highlights and Flat PBR]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
