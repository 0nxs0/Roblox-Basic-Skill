---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Obby Stage Save and Skip Stage Product.md"
---
# Recipe - Obby Stage Save and Skip Stage Product — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Obby Stage Save and Skip Stage Product|Recipe - Obby Stage Save and Skip Stage Product]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Obby progress that survives leaving the game, respawns at the furthest checkpoint, and a "Skip stage" button sold as a developer product. The 30-minute starter in First Obby in 30 Minutes keeps stages for one session only; returning players who lose 40 stages of progress usually do not come back, and the skip-stage product is one of the most common obby monetization items. Checkpoints here are `SpawnLocation`s,...
**Useful source sections:** Where it goes, Server, Skip stage: one more grant in the receipt handler.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Obby Stage Save and Skip Stage Product, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Obby Stage Save and Skip Stage Product and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Obby Stage Save and Skip Stage Product|Recipe - Obby Stage Save and Skip Stage Product]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
