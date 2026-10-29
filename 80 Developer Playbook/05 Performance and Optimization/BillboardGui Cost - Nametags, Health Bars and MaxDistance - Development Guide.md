---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/BillboardGui Cost - Nametags, Health Bars and MaxDistance.md"
---
# BillboardGui Cost - Nametags, Health Bars and MaxDistance — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/BillboardGui Cost - Nametags, Health Bars and MaxDistance|BillboardGui Cost - Nametags, Health Bars and MaxDistance]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Overhead UI is everywhere in Roblox games: nametags, NPC health bars, damage numbers, shop prices floating over items, quest markers. Each one is a `BillboardGui` that the client renders in 3D every frame it is visible. One or two dozen are cheap; a tower-defense lane with 200 enemies, each with a health bar and a level label, is not. The cost is easy to miss in Studio on a strong PC and obvious on a phone.
**Useful source sections:** What is known, Budget rules, Implementation pattern: show on damage.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For BillboardGui Cost - Nametags, Health Bars and MaxDistance, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using BillboardGui Cost - Nametags, Health Bars and MaxDistance and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/BillboardGui Cost - Nametags, Health Bars and MaxDistance|BillboardGui Cost - Nametags, Health Bars and MaxDistance]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
