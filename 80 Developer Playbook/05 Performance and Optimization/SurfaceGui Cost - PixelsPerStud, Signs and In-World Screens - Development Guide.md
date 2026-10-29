---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Perf - SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens.md"
---
# SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Perf - SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens|SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
SurfaceGuis put 2D UI on the face of a part: shop signs, scoreboards, computer screens, door labels, tycoon buttons. One is harmless. A mall map with 300 signs, each a SurfaceGui full of TextLabels, is a real client cost: every one is a UI tree that has to be laid out and drawn in 3D, whether the player is looking at it or not. The BillboardGui note covers floating UI over heads; this one covers UI glued to...
**Useful source sections:** The properties that matter, Rules of thumb, Interactive surfaces.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Perf - SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens|SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
