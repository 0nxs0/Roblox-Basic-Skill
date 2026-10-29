---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Perf - Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup.md"
---
# Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Perf - Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup|Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Audio rarely shows up in the MicroProfiler as a big spike, so it is easy to ignore, but it is one of the top client memory consumers. Roblox's "Identify performance issues" guide lists Sounds next to mesh and texture memory as the usual big client categories, and the Developer Console splits audio into `Sounds` (loaded into memory) and `StreamingSounds` (long tracks streamed). A game that ships 400 unique sound...
**Useful source sections:** Where the cost comes from, Rules of thumb, Loading.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Perf - Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup|Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
