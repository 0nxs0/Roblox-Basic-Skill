---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Fight - Melee Weapon Archetypes - Reach, Speed, Cleave and Charge.md"
---
# Melee Weapon Archetypes - Reach, Speed, Cleave and Charge — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Fight - Melee Weapon Archetypes - Reach, Speed, Cleave and Charge|Melee Weapon Archetypes - Reach, Speed, Cleave and Charge]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A melee roster where every weapon is "sword with more damage" collapses to the newest sword. Variety comes from trading off a few axes: reach, speed, number of targets (cleave), commitment (wind-up and recovery) and charge. Minecraft Java is a well documented example of a tiny ruleset that creates real choices: an attack cooldown scales damage, swords sweep, and crits need conditions.
**Useful source sections:** The axes, Minecraft's rules as a reference, Five starter archetypes for a Roblox game.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Melee Weapon Archetypes - Reach, Speed, Cleave and Charge, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Melee Weapon Archetypes - Reach, Speed, Cleave and Charge and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Fight - Melee Weapon Archetypes - Reach, Speed, Cleave and Charge|Melee Weapon Archetypes - Reach, Speed, Cleave and Charge]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
