---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity.md"
---
# Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity|Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every BasePart carries four collision switches, and almost every map ships with them left at the defaults. Decorative props, foliage and trim then take part in physics broadphase, raycasts, touch events and physics memory for no gameplay reason. Tuning them is one of the cheapest wins on large maps: no art changes, no visual difference, and fewer surprises for weapon raycasts that hit grass.
**Useful source sections:** What each switch actually does (Engine API), CollisionFidelity choices, A prop profile table to agree on as a team.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity|Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
