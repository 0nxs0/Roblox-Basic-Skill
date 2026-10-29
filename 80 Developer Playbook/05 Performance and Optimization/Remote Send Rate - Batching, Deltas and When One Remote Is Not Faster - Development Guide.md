---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster.md"
---
# Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster|Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Remote traffic is the one performance cost that hurts the server, every client and every player's ping at the same time. The Improve Performance guide lists the usual causes: replicating data every frame that does not need it, firing on input without throttling, and sending whole tables when one field changed. This note is about how much and how often you send. Payload packing (buffers, bit packing) and security...
**Useful source sections:** The order of wins, What the community says about batching, A small per-frame batcher (server to clients).

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster|Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
