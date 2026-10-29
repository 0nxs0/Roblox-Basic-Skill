---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - Arsenal.md"
---
# Case Study - Arsenal — Development Guide

New practical guidance for [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - Arsenal|Case Study - Arsenal]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Arsenal (ROLVe) is an arcade shooter where every kill swaps your weapon for the next one in a rotation, and the first player through the full list wins (a Gun Game format). It matters because it was the first Roblox FPS to 1 billion visits and shows how a fair shooter monetizes almost only with characters, effects and bundles.
**Useful source sections:** Snapshot (Roblox page, seen 2026-10-25), Core loop, Session shape.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Case Study - Arsenal, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Case Study - Arsenal and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - Arsenal|Case Study - Arsenal]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
