---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Inventory Economy/Community Knowledge/XP Curve Formulas - Time-to-Level Targets and Level Caps.md"
---
# XP Curve Formulas - Time-to-Level Targets and Level Caps — Development Guide

New practical guidance for [[02 Game Design and Economy/Inventory Economy/Community Knowledge/XP Curve Formulas - Time-to-Level Targets and Level Caps|XP Curve Formulas - Time-to-Level Targets and Level Caps]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A level system is a promise about time: "Level 10 takes about an hour". Most broken progression comes from picking a formula first and discovering its time-to-level later. Design backwards: decide how long levels should take, then fit the formula. This note gives the common curve shapes, how to convert them into minutes, and a Luau helper.
**Useful source sections:** Step 1: target time per level, not XP, Step 2: pick a curve shape, Step 3: helper module.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For XP Curve Formulas - Time-to-Level Targets and Level Caps, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using XP Curve Formulas - Time-to-Level Targets and Level Caps and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Inventory Economy/Community Knowledge/XP Curve Formulas - Time-to-Level Targets and Level Caps|XP Curve Formulas - Time-to-Level Targets and Level Caps]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
