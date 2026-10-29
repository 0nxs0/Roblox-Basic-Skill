---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs.md"
---
# Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs|Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most client memory in a finished game is assets: textures, meshes and sounds. The surprise for many creators is that file size on disk does not predict memory. A 200 KB JPG and a 4 MB PNG at the same resolution cost the same graphics memory once loaded. This note collects the rules that actually move memory, with the official limits, so you can set upload standards for your team before the art pile grows.
**Useful source sections:** Textures: pixels are the cost, Meshes, Audio.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs|Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
