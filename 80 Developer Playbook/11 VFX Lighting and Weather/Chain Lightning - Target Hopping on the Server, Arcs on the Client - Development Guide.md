---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Chain Lightning - Target Hopping on the Server, Arcs on the Client.md"
---
# Chain Lightning - Target Hopping on the Server, Arcs on the Client — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Chain Lightning - Target Hopping on the Server, Arcs on the Client|Chain Lightning - Target Hopping on the Server, Arcs on the Client]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Chain lightning (hit one enemy, jump to the next, and the next) is a staple of tower defense and RPG games. The DevForum thread in the sources is a typical question: a tower can hit one target and chain once, but the developer wants it to keep hopping to new unshocked enemies. The answer is a small loop that is the same in every engine: from the last target, pick the nearest enemy you have not hit yet, within...
**Useful source sections:** Server: pick the chain, Client: draw each arc, Pitfalls.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Chain Lightning - Target Hopping on the Server, Arcs on the Client, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Chain Lightning - Target Hopping on the Server, Arcs on the Client and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Chain Lightning - Target Hopping on the Server, Arcs on the Client|Chain Lightning - Target Hopping on the Server, Arcs on the Client]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
