---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup.md"
---
# Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup|Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most first cutscenes on Roblox are a long chain of `tween:Play()` and `task.wait(2)`. That works until you need to skip, start halfway for a late joiner, pause, or stop cleanly when the player dies. A yield chain cannot jump to second 7.5; it can only wait through it. The fix is a small timeline runner: the cutscene is data (tracks of keyed events on a shared clock) and one function evaluates "what should be true...
**Useful source sections:** Cutscene as data, The runner loop, Skipping = apply the end state.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup|Cutscene Timeline Runner - Tracks, Seeking and Safe Cleanup]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
