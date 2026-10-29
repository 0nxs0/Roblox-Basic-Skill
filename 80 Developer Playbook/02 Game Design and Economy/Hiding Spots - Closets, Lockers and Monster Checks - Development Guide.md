---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Hiding Spots - Closets, Lockers and Monster Checks.md"
---
# Hiding Spots - Closets, Lockers and Monster Checks — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Hiding Spots - Closets, Lockers and Monster Checks|Hiding Spots - Closets, Lockers and Monster Checks]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Hiding is the main verb of chase horror on Roblox: DOORS closets, Piggy-style houses, locker rooms in school horror games. A hiding system is small (a prompt, a seat-like position, a flag the monster reads) but it decides whether the game is tense or trivial. If hiding is perfectly safe, players camp in the closet. If it is random, they feel cheated. The goal is safe if you chose well and timed it well, risky if...
**Useful source sections:** Core data, Clean-up rules (where most bugs live), Camera and feel (client).

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Hiding Spots - Closets, Lockers and Monster Checks, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Hiding Spots - Closets, Lockers and Monster Checks and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Hiding Spots - Closets, Lockers and Monster Checks|Hiding Spots - Closets, Lockers and Monster Checks]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
