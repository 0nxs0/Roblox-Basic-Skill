---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/Materials Textures/Texture and PBR Specs — 2026 Snapshot.md"
---
# Texture and PBR Specs — 2026 Snapshot — Development Guide

New practical guidance for [[10 3D Art and Materials/Materials Textures/Texture and PBR Specs — 2026 Snapshot|Texture and PBR Specs — 2026 Snapshot]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox currently documents: - uploaded texture files can support resolutions up to 4096×4096 in relevant general workflows - manually reducing resolution can improve memory - example guidance: small 5×5 stud object 256², medium 10×10 512², larger 20×20 1024² - SurfaceAppearance supports Color/Albedo, Normal, Roughness, Metalness, and Emissive Mask maps - normal maps use OpenGL tangent-space convention - a mesh...
**Useful source sections:** Knowledge Graph Connections.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Texture and PBR Specs — 2026 Snapshot, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Texture and PBR Specs — 2026 Snapshot and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/Materials Textures/Texture and PBR Specs — 2026 Snapshot|Texture and PBR Specs — 2026 Snapshot]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
