---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Inventory Economy/Community Knowledge/Pity Timers and Pseudo-Random Distribution.md"
---
# Pity Timers and Pseudo-Random Distribution — Development Guide

New practical guidance for [[02 Game Design and Economy/Inventory Economy/Community Knowledge/Pity Timers and Pseudo-Random Distribution|Pity Timers and Pseudo-Random Distribution]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
True randomness feels unfair. With a 1% drop, about 37% of players still have nothing after 100 tries ((0.99)^100 = 0.366), and those are the players who post angry reviews and quit. Two well-known tools fix this without changing the advertised average: pity counters (guarantee after N misses) and pseudo-random distribution (PRD, chance grows after each miss). Both are standard in shipped games and easy to build...
**Useful source sections:** Option 1: Hard pity (guarantee at N), Option 2: PRD (Warcraft III / Dota 2 style), Disclosure and honesty.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Pity Timers and Pseudo-Random Distribution, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Pity Timers and Pseudo-Random Distribution and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Inventory Economy/Community Knowledge/Pity Timers and Pseudo-Random Distribution|Pity Timers and Pseudo-Random Distribution]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
