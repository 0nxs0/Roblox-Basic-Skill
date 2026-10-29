---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Deep Dives/Instance Count and Part Budgets.md"
---
# Instance Count and Part Budgets — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Deep Dives/Instance Count and Part Budgets|Instance Count and Part Budgets]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox does not publish hard instance limits; the budget numbers below are team starting points to measure against on your target devices, not engine rules. Texture and triangle budgets are covered in Texture Memory and Triangle Budgets for Roblox Scenes.
**Useful source sections:** 1. What an instance costs, 2. Measure first: the audit script, 3. A starting budget table.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Instance Count and Part Budgets, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Instance Count and Part Budgets and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Deep Dives/Instance Count and Part Budgets|Instance Count and Part Budgets]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
