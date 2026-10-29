---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology.md"
---
# Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology|Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Lighting is the part of a Roblox scene where a builder can lose 5 ms of GPU time without adding a single part. A street of shadow-casting point lights, a forest where every leaf mesh casts shadows, or a Future-lit interior with 40 lamps all look fine on a desktop GPU and stall phones. The fixes are mostly property changes, so they are worth knowing before the art pass, not after the launch.
**Useful source sections:** What the engine does (official guidance), What a Roblox rendering engineer added, Community experience.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology|Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
