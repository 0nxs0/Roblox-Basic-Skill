---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Threat Tables and Target Selection for Enemies.md"
---
# Threat Tables and Target Selection for Enemies — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Threat Tables and Target Selection for Enemies|Threat Tables and Target Selection for Enemies]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most Roblox enemies target "the closest player", which makes co-op combat shallow: the tank cannot protect anyone, ranged players are never punished, and the enemy flips targets every frame when two players stand at similar distances. MMOs solved this long ago with threat tables. In World of Warcraft each NPC keeps a list of everyone who has threatened it; damage adds threat (one point per point of damage as the...
**Useful source sections:** The table, Switching rules (the part that makes it feel right), Decay and leashing.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Threat Tables and Target Selection for Enemies, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Threat Tables and Target Selection for Enemies and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Threat Tables and Target Selection for Enemies|Threat Tables and Target Selection for Enemies]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
