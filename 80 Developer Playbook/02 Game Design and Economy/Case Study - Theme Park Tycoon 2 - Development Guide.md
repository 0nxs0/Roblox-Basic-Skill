---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - Theme Park Tycoon 2.md"
---
# Case Study - Theme Park Tycoon 2 — Development Guide

New practical guidance for [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - Theme Park Tycoon 2|Case Study - Theme Park Tycoon 2]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Theme Park Tycoon 2 (DenS, solo developer) is a freeform park builder in the RollerCoaster Tycoon tradition: build rides and custom coasters, place paths and scenery, keep guests happy and clean, and grow income. It matters because it is the opposite of a "button tycoon": it is a real creative builder that has lasted since 2012, and its passes sell building freedom, not money.
**Useful source sections:** Snapshot (Roblox page, seen 2026-10-25), Core loop, Session shape.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Case Study - Theme Park Tycoon 2, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Case Study - Theme Park Tycoon 2 and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Foundations Planning/Community Knowledge/Case Study - Theme Park Tycoon 2|Case Study - Theme Park Tycoon 2]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
