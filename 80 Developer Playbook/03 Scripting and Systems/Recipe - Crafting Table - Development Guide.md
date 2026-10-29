---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Crafting Table.md"
---
# Recipe - Crafting Table — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Crafting Table|Recipe - Crafting Table]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Walk up to a workbench, press E, pick a recipe, and turn materials (wood, cloth, scrap) into items. Survival and simulator games live on this loop. The design side (recipe tiers, sinks) is in Crafting System Blueprint; this note is the working code: recipes as shared data, a server that re-checks everything (recipe exists, you are at a table, you have the materials), and a small UI built in code.
**Useful source sections:** Where it goes, Recipes (shared data), Server.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Crafting Table, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Crafting Table and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Crafting Table|Recipe - Crafting Table]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
