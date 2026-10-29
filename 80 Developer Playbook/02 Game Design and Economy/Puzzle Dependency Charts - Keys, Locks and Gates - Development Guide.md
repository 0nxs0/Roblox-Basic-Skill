---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Puzzle Dependency Charts - Keys, Locks and Gates.md"
---
# Puzzle Dependency Charts - Keys, Locks and Gates — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Puzzle Dependency Charts - Keys, Locks and Gates|Puzzle Dependency Charts - Keys, Locks and Gates]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Piggy-style chapters, escape rooms and story obbies are all built on the same skeleton: you need X to get Y. Find the key, open the door, get the wrench, fix the generator, power the gate, escape. When this skeleton is badly shaped, players hit dead ends, wander with nothing to do, or solve everything in one straight line. Ron Gilbert (Monkey Island) designed with puzzle dependency charts and explained the method...
**Useful source sections:** What the chart is (and is not), How to draw one, Shapes to look for.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Puzzle Dependency Charts - Keys, Locks and Gates, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Puzzle Dependency Charts - Keys, Locks and Gates and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Puzzle Dependency Charts - Keys, Locks and Gates|Puzzle Dependency Charts - Keys, Locks and Gates]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
