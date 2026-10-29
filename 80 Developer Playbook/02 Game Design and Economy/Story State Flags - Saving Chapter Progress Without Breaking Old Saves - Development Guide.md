---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Story State Flags - Saving Chapter Progress Without Breaking Old Saves.md"
---
# Story State Flags - Saving Chapter Progress Without Breaking Old Saves — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Story State Flags - Saving Chapter Progress Without Breaking Old Saves|Story State Flags - Saving Chapter Progress Without Breaking Old Saves]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A story game's save is not just coins and items. It records what the player has seen and decided: which chapters are done, which NPCs are alive, which notes were found, which ending was reached. Story saves have their own failure modes. A renamed flag silently resets a choice. A new chapter added in an update leaves old saves in an impossible state. A co-op party mixes players at different points of the story....
**Useful source sections:** Shape: three kinds of story data, Rules that prevent broken saves, When to save.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Story State Flags - Saving Chapter Progress Without Breaking Old Saves, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Story State Flags - Saving Chapter Progress Without Breaking Old Saves and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Story State Flags - Saving Chapter Progress Without Breaking Old Saves|Story State Flags - Saving Chapter Progress Without Breaking Old Saves]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
