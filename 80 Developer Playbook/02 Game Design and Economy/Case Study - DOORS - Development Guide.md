---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - DOORS.md"
---
# Case Study - DOORS — Development Guide

New practical guidance for [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - DOORS|Case Study - DOORS]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
DOORS (LSPLASH) is a co-op roguelite horror game: open numbered doors through a procedurally arranged hotel while "entities" try to kill you, each with its own rule you must learn. It matters because it shows how to make horror replayable: learnable monster rules, short deaths, and a group that watches each other scream.
**Useful source sections:** Snapshot (Roblox page, seen 2026-10-25), Core loop, Session shape.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Case Study - DOORS, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Case Study - DOORS and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - DOORS|Case Study - DOORS]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
