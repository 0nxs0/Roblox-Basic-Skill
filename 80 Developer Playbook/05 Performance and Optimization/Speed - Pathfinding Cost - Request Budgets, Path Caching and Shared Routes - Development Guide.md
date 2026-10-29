---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes.md"
---
# Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes|Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`Path:ComputeAsync` is cheap once and expensive at scale. A horde of 60 zombies each recomputing every half second is 120 path searches per second on the server, most of them returning almost the same route as last time. DevForum threads keep landing on the same advice: compute less often, share results, and do not pathfind when a straight line works. This note turns that into a budget and a cache you can drop...
**Useful source sections:** Step 1: avoid the search entirely, Step 2: a server-wide request budget, Step 3: cache by cell.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes|Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
