---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Unions vs MeshParts - When CSG Costs More Than It Saves.md"
---
# Unions vs MeshParts - When CSG Costs More Than It Saves — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Unions vs MeshParts - When CSG Costs More Than It Saves|Unions vs MeshParts - When CSG Costs More Than It Saves]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Studio's solid modeling tools (Union, Intersect, Negate, Subtract) make it fast to cut windows, arches and pipes without leaving Studio. The question every builder eventually asks is whether those unions are slower than a MeshPart from Blender. The honest answer from the forum is "it depends on triangles, reuse and collision", and there is no official benchmark. This note collects what is documented and what the...
**Useful source sections:** What is documented, What the community reports (not benchmarks), A decision table.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Unions vs MeshParts - When CSG Costs More Than It Saves, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Unions vs MeshParts - When CSG Costs More Than It Saves and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Unions vs MeshParts - When CSG Costs More Than It Saves|Unions vs MeshParts - When CSG Costs More Than It Saves]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
