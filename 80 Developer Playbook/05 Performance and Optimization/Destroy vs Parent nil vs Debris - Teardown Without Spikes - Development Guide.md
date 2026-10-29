---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Perf - Destroy vs Parent nil vs Debris - Teardown Without Spikes.md"
---
# Destroy vs Parent nil vs Debris - Teardown Without Spikes — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Perf - Destroy vs Parent nil vs Debris - Teardown Without Spikes|Destroy vs Parent nil vs Debris - Teardown Without Spikes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Removing objects is as much a performance topic as creating them. The three common ways to get rid of an instance behave very differently: one frees connections, one keeps the object alive for reuse, and one has a hidden cap. Picking the wrong one causes either slow memory growth (objects that never die) or frame spikes (thousands of objects dying in the same frame). This note is about choosing the right teardown...
**Useful source sections:** What each option actually does, Pick by use case, Avoiding teardown spikes.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Destroy vs Parent nil vs Debris - Teardown Without Spikes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Destroy vs Parent nil vs Debris - Teardown Without Spikes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Perf - Destroy vs Parent nil vs Debris - Teardown Without Spikes|Destroy vs Parent nil vs Debris - Teardown Without Spikes]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
