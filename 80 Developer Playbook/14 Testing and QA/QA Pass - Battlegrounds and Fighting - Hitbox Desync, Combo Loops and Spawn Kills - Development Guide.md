---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills.md"
---
# QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills|QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Battlegrounds games are judged in milliseconds. Players forgive ugly maps but not a hit that "should have landed", a combo that never lets them move, or dying the moment they spawn. This pass is the genre layer on top of the general combat checklist: it tests fairness under real ping, stun-lock loops and the spawn area.
**Useful source sections:** Bugs this genre always ships with, Test checklist, Exploit angles.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills|QA Pass - Battlegrounds and Fighting - Hitbox Desync, Combo Loops and Spawn Kills]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
