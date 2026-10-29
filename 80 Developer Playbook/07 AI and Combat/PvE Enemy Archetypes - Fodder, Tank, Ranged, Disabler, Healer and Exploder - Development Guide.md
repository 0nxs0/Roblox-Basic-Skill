---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder.md"
---
# PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder|PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A wave of 30 identical zombies is a DPS check, not an encounter. Good PvE games build enemies as roles that each ask the player a different question, then mix roles so the player must prioritize. DOOM (2016) shipped 16 AI archetypes, each with distinct behavior (Tommy Thompson's Game Developer write-up: imps keep distance and throw fireballs, pinkies charge, hell knights lunge). Left 4 Dead's special infected are...
**Useful source sections:** The core roles, Rules that make roles readable, Implementation pattern on Roblox.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder|PvE Enemy Archetypes - Fodder, Tank, Ranged, Disabler, Healer and Exploder]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
