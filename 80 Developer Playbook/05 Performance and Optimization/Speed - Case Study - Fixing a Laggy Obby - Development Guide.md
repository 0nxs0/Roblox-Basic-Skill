---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Speed - Case Study - Fixing a Laggy Obby.md"
---
# Speed - Case Study - Fixing a Laggy Obby — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Case Study - Fixing a Laggy Obby|Speed - Case Study - Fixing a Laggy Obby]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Obbies look simple, so their lag is usually self-inflicted: hundreds of copy-pasted kill-brick scripts, spinning parts driven from the server, a 600-stage map that fully replicates on join, and free-model decorations. This walkthrough is a typical "my obby lags on phones" fix, in the order you should measure and fix. The symptoms and causes come from DevForum threads; the fixes follow the Creator Hub performance...
**Useful source sections:** Symptoms players report, Step 1: measure before touching anything, Step 2: the usual culprits, in order of payoff.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - Case Study - Fixing a Laggy Obby, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - Case Study - Fixing a Laggy Obby and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Case Study - Fixing a Laggy Obby|Speed - Case Study - Fixing a Laggy Obby]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
