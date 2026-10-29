---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame.md"
---
# BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame|BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Client-rendered crowds, RTS units, projectile visuals, conveyor items and tower-defense enemies often end up as hundreds of anchored parts whose `CFrame` is set every frame. Each separate assignment fires property-changed signals and pays its own engine call. `WorldRoot:BulkMoveTo` moves a whole array in one call and can skip most of those signals. It is the standard tool once part movement shows up as the top...
**Useful source sections:** The API (Engine API), A reusable pattern, What the community measured.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame|BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
