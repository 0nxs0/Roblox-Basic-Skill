---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances.md"
---
# Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances|Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Scene Analysis is a Studio window that answers "what is this place made of, and who is holding it in memory?" as a treemap, for the client or the server, during a play test. It is faster than digging through the Developer Console when you do not yet know where to look. This walkthrough runs it as a leak hunt and a scene audit, and shows the matching APIs for automating the same checks.
**Useful source sections:** Open it, The six modes and what to look for, Leak hunt routine.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances|Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
