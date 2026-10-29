---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - Credit-Based Spawn Director and Player-Count Scaling.md"
---
# Credit-Based Spawn Director and Player-Count Scaling — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - Credit-Based Spawn Director and Player-Count Scaling|Credit-Based Spawn Director and Player-Count Scaling]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox co-op servers swing from 1 player to 12 and back within minutes. A wave script tuned for 4 players is boring for 12 and impossible for 1. Risk of Rain 2 solves this with a credit director: the director earns "credits" over time, scaled by difficulty and player count, and buys enemies from a weighted catalog. The Risk of Rain 2 wiki documents the formulas, which makes it an ideal reference to copy.
**Useful source sections:** How Risk of Rain 2's combat director works (per the wiki), A Roblox version, Difficulty coefficient over time.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Credit-Based Spawn Director and Player-Count Scaling, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Credit-Based Spawn Director and Player-Count Scaling and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - Credit-Based Spawn Director and Player-Count Scaling|Credit-Based Spawn Director and Player-Count Scaling]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
