---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - 99 Nights in the Forest.md"
---
# Case Study - 99 Nights in the Forest — Development Guide

New practical guidance for [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - 99 Nights in the Forest|Case Study - 99 Nights in the Forest]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
99 Nights in the Forest (Grandma's Favourite Games: Alec Kieft, Cameron Angland, Matthew Hufton, New Zealand) is a co-op survival horror game: keep a campfire burning, craft defenses, explore a forest for resources and rescue four lost kids while the Deer and cultists hunt you. It matters most for survival and zombie projects: it shows how a single central object (the fire) and a countdown goal ("99 nights") make...
**Useful source sections:** Snapshot (Roblox page, seen 2026-10-25), Core loop, Session shape.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Case Study - 99 Nights in the Forest, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Case Study - 99 Nights in the Forest and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - 99 Nights in the Forest|Case Study - 99 Nights in the Forest]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
