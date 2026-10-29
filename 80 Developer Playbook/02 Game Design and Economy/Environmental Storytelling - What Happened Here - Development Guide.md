---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Environmental Storytelling - What Happened Here.md"
---
# Environmental Storytelling - What Happened Here — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Environmental Storytelling - What Happened Here|Environmental Storytelling - What Happened Here]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox players skip text. Many are young, many play on phones, and most cutscenes get skipped. Story that lives in the space itself (a barricaded door, a trail of dropped items, a half-eaten meal) is read in a glance and works in every language. The best-known framework is the GDC 2010 talk What Happened Here? Environmental Storytelling by Harvey Smith (Arkane) and Matthias Worch (LucasArts).
**Useful source sections:** The core idea, A clue recipe you can build in Studio, Roblox-specific tips.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Environmental Storytelling - What Happened Here, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Environmental Storytelling - What Happened Here and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Environmental Storytelling - What Happened Here|Environmental Storytelling - What Happened Here]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
