---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Stalker Monster AI Feel - Director Leash, Senses and Fair Kills.md"
---
# Stalker Monster AI Feel - Director Leash, Senses and Fair Kills — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Stalker Monster AI Feel - Director Leash, Senses and Fair Kills|Stalker Monster AI Feel - Director Leash, Senses and Fair Kills]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A single unkillable monster that hunts players through the map (Piggy, the Alien, most "escape the house" games) is only scary if players believe two things: it could find me at any moment, and when it catches me, it was my fault. If the monster cheats (walks straight to a hidden player), players feel robbed. If it is dumb, it is not scary. The best documented answer is Alien: Isolation's two-layer AI, described...
**Useful source sections:** Two brains, Senses the player can understand, Search like it is unsure.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Stalker Monster AI Feel - Director Leash, Senses and Fair Kills, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Stalker Monster AI Feel - Director Leash, Senses and Fair Kills and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Stalker Monster AI Feel - Director Leash, Senses and Fair Kills|Stalker Monster AI Feel - Director Leash, Senses and Fair Kills]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
