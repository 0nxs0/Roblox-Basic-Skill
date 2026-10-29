---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Inventory Economy/Community Knowledge/Incremental Cost Curves - Exponential Costs and Bulk Buy Math.md"
---
# Incremental Cost Curves - Exponential Costs and Bulk Buy Math — Development Guide

New practical guidance for [[02 Game Design and Economy/Inventory Economy/Community Knowledge/Incremental Cost Curves - Exponential Costs and Bulk Buy Math|Incremental Cost Curves - Exponential Costs and Bulk Buy Math]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Simulators, tycoons and idle games on Roblox all run on the same engine: the player buys "generators" (droppers, pets, workers, upgrades) whose price climbs faster than their output. If you get this curve wrong the game either stalls in the first ten minutes or is "finished" in an hour. Anthony Pecorella (Kongregate, producer of AdVenture Capitalist) published the clearest public write-up of this math; this note...
**Useful source sections:** The two formulas, Bulk buy ("Buy x10", "Buy Max"), Multipliers and milestones.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Incremental Cost Curves - Exponential Costs and Bulk Buy Math, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Incremental Cost Curves - Exponential Costs and Bulk Buy Math and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Inventory Economy/Community Knowledge/Incremental Cost Curves - Exponential Costs and Bulk Buy Math|Incremental Cost Curves - Exponential Costs and Bulk Buy Math]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
