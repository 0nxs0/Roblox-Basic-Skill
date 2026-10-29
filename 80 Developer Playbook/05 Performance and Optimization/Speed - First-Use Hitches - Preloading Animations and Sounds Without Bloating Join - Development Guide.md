---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join.md"
---
# Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join|Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The first time a player swings a new weapon, the swing animation is late or missing and the hit sound is silent; the second swing is fine. That is a first-use hitch: the asset was downloaded on demand. Preloading everything at join fixes the hitch but makes join slower and wastes memory, which the Creator Hub specifically warns against. The right strategy is just-ahead-of-time loading: load assets when the player...
**Useful source sections:** Animations, Sounds, What to preload at join vs later.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join|Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
