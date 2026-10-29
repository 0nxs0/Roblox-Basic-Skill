---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Speed - Connection Leak Finder - Counting Live Connections by Tag.md"
---
# Speed - Connection Leak Finder - Counting Live Connections by Tag — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Connection Leak Finder - Counting Live Connections by Tag|Speed - Connection Leak Finder - Counting Live Connections by Tag]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Memory tools tell you that memory is growing; they rarely tell you which `:Connect` call is responsible. Leaked connections are the classic cause the Creator Hub names: a connected callback and every value it captures stay alive until the connection is disconnected or its instance is destroyed. A small debug wrapper that counts live connections per call site turns "LuaHeap goes up" into "Shop.openButton has 340...
**Useful source sections:** The idea, The tracker, Using it.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - Connection Leak Finder - Counting Live Connections by Tag, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - Connection Leak Finder - Counting Live Connections by Tag and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - Connection Leak Finder - Counting Live Connections by Tag|Speed - Connection Leak Finder - Counting Live Connections by Tag]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
