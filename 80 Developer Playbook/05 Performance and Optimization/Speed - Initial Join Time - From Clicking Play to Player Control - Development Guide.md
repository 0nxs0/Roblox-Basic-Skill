---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Speed - Initial Join Time - From Clicking Play to Player Control.md"
---
# Speed - Initial Join Time - From Clicking Play to Player Control — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Speed - Initial Join Time - From Clicking Play to Player Control|Speed - Initial Join Time - From Clicking Play to Player Control]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Join time is the first thing every player experiences and the easiest place to lose them: a long black or spinner screen on a phone is a quit. The Creator Hub defines load time as everything from clicking Play until the world renders and the player can act. This note breaks that into stages, shows how to time each one, and lists fixes by stage. (Preloading specifically is covered in PreloadAsync and Loading...
**Useful source sections:** The stages (official order), Time each stage, Fixes by stage.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - Initial Join Time - From Clicking Play to Player Control, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - Initial Join Time - From Clicking Play to Player Control and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Speed - Initial Join Time - From Clicking Play to Player Control|Speed - Initial Join Time - From Clicking Play to Player Control]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
