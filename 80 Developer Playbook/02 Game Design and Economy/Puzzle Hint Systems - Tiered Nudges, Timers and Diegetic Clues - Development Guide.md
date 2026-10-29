---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues.md"
---
# Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues|Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
On Roblox a stuck player does not open a walkthrough; they leave, and they take their friends with them. Puzzle and escape games therefore need a hint system that rescues stuck players without spoiling the "aha" for everyone else. Adventure games solved this decades ago with escalating hints: the first hint is vague, each later one is more direct, and the final one is the answer. This note turns that into a...
**Useful source sections:** Patterns that have worked, Three tiers for every lock, When to offer hints.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues|Puzzle Hint Systems - Tiered Nudges, Timers and Diegetic Clues]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
