---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Luau GC Pressure - What Allocates and How to Cut It.md"
---
# Luau GC Pressure - What Allocates and How to Cut It — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Luau GC Pressure - What Allocates and How to Cut It|Luau GC Pressure - What Allocates and How to Cut It]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Luau's garbage collector rarely causes a single dramatic freeze, but code that allocates heavily every frame pays for it twice: once to build the garbage and again in collector work that the engine interleaves with your scripts. On phones this shows up as a steady few milliseconds of script time that never goes away. The fix is not "avoid tables"; it is knowing which lines allocate in hot paths (per-frame loops,...
**Useful source sections:** How the Luau collector works (luau.org Performance page), What allocates, Fixes that matter in hot paths.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Luau GC Pressure - What Allocates and How to Cut It, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Luau GC Pressure - What Allocates and How to Cut It and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Luau GC Pressure - What Allocates and How to Cut It|Luau GC Pressure - What Allocates and How to Cut It]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
