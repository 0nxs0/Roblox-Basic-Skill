---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Horror Flashlights - Aim, Battery, Replication and Shadow Budget.md"
---
# Horror Flashlights - Aim, Battery, Replication and Shadow Budget — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Horror Flashlights - Aim, Battery, Replication and Shadow Budget|Horror Flashlights - Aim, Battery, Replication and Shadow Budget]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In a dark horror map the flashlight is the camera, the UI and the main resource all at once. Where it points is what the player knows. When it dies, the game gets scarier without a single new monster. A beginner flashlight (a Tool with a `SpotLight` you toggle) is covered in First Tool - A Sword or Flashlight You Can Equip, and general light costs in Local Light Budgets - PointLight, SpotLight and SurfaceLight....
**Useful source sections:** 1. Aim with the camera, not the hand, 2. Settings that look good and stay cheap, 3. Battery as tension.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Horror Flashlights - Aim, Battery, Replication and Shadow Budget, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Horror Flashlights - Aim, Battery, Replication and Shadow Budget and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Horror Flashlights - Aim, Battery, Replication and Shadow Budget|Horror Flashlights - Aim, Battery, Replication and Shadow Budget]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
