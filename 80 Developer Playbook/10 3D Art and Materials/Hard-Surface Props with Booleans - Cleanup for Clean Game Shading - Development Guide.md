---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Hard-Surface Props with Booleans - Cleanup for Clean Game Shading.md"
---
# Hard-Surface Props with Booleans - Cleanup for Clean Game Shading — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Hard-Surface Props with Booleans - Cleanup for Clean Game Shading|Hard-Surface Props with Booleans - Cleanup for Clean Game Shading]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Booleans (cutting or adding one shape with another) are the fastest way to model vents, doorways, panel cuts and machinery. Left as they are, they export as long thin triangles and n-gons that shade with dark smears in Roblox, waste triangles, and break bevels. A short cleanup routine turns boolean results into clean, light game meshes. It applies equally to Studio's own solid modeling (Unions), which is why many...
**Useful source sections:** Boolean modifier basics (Blender), Cleanup routine after applying, Keep triangle count in check.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Hard-Surface Props with Booleans - Cleanup for Clean Game Shading, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Hard-Surface Props with Booleans - Cleanup for Clean Game Shading and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Art - Hard-Surface Props with Booleans - Cleanup for Clean Game Shading|Hard-Surface Props with Booleans - Cleanup for Clean Game Shading]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
