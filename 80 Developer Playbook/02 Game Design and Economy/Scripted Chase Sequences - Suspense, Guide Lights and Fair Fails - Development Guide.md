---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails.md"
---
# Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails|Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A scripted chase (the monster bursts out and you run down a corridor, through a collapsing room, to a door that slams just in time) is the set piece players remember and clip for videos. It is different from a free-roaming stalker (Story - Stalker Monster AI Feel - Director Leash, Senses and Fair Kills): the route is fixed, the monster is choreographed, and the whole thing lasts 20-60 seconds. Done well it is...
**Useful source sections:** Suspense first, then the run, Make the route readable at a sprint, Monster speed and rubber-banding.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails|Scripted Chase Sequences - Suspense, Guide Lights and Fair Fails]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
