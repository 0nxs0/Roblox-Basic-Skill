---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Performance/Community Knowledge/Perf - ViewportFrame Cost - Item Previews Without Frame Drops.md"
---
# ViewportFrame Cost - Item Previews Without Frame Drops — Development Guide

New practical guidance for [[05 Performance and Optimization/Performance/Community Knowledge/Perf - ViewportFrame Cost - Item Previews Without Frame Drops|ViewportFrame Cost - Item Previews Without Frame Drops]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
ViewportFrames render 3D objects inside 2D UI: spinning pets in a shop, weapon icons in an inventory, a character preview on the customise screen, a minimap. Each one is a small extra 3D render inside your UI, with its own camera and its own set of meshes and textures held in memory. An inventory grid with 60 live ViewportFrames, each holding a full-detail model and rotating every frame, is a classic "the menu...
**Useful source sections:** How a ViewportFrame works (official), Cost rules, Pattern: camera orbit on one preview.

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For ViewportFrame Cost - Item Previews Without Frame Drops, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using ViewportFrame Cost - Item Previews Without Frame Drops and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Performance/Community Knowledge/Perf - ViewportFrame Cost - Item Previews Without Frame Drops|ViewportFrame Cost - Item Previews Without Frame Drops]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
