---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes.md"
---
# Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes|Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Single-player checkpoint rules break in co-op. If a dead player respawns at the start, they are out of the story for ten minutes. If they respawn next to the party instantly, death means nothing and horror stops being scary. If the party wipes, do they restart the chapter, the room, or the run? Roblox makes this sharper because players join and leave mid-run. This note gives a small rule set for respawn, catch-up...
**Useful source sections:** Pick a death model (one per mode), Checkpoints are per party, not per player, Measuring "behind": flow distance.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes|Co-op Story Checkpoints - Respawn, Catch-Up and Party Wipes]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
