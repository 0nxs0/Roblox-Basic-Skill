---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA Pass - Survival - Resource Respawns, Base Griefing and Raids.md"
---
# QA Pass - Survival - Resource Respawns, Base Griefing and Raids — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA Pass - Survival - Resource Respawns, Base Griefing and Raids|QA Pass - Survival - Resource Respawns, Base Griefing and Raids]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Survival games mix three systems that each break in their own way: a world that refills (trees, ore, loot crates), a building system where players change the map, and other players who want to wreck what you built. Bugs here are rarely crashes. They are slow economic leaks (resources farmed by server hopping) and social damage (spawn trapping, offline raids) that drive players away.
**Useful source sections:** Bugs this genre always ships with, Test checklist, Exploit angles.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA Pass - Survival - Resource Respawns, Base Griefing and Raids, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA Pass - Survival - Resource Respawns, Base Griefing and Raids and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA Pass - Survival - Resource Respawns, Base Griefing and Raids|QA Pass - Survival - Resource Respawns, Base Griefing and Raids]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
