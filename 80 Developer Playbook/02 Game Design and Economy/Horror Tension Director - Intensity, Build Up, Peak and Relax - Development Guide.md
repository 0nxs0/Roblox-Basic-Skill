---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Horror Tension Director - Intensity, Build Up, Peak and Relax.md"
---
# Horror Tension Director - Intensity, Build Up, Peak and Relax — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Horror Tension Director - Intensity, Build Up, Peak and Relax|Horror Tension Director - Intensity, Build Up, Peak and Relax]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A horror game that is scary all the time stops being scary. Players go numb, then bored, then they leave. The fix most big horror and co-op games use is a small director script that watches how stressed players are and turns the threat up or down. Valve's Left 4 Dead director (Michael Booth, "The AI Systems of Left 4 Dead", 2009) is the best documented version, and its rules fit a Roblox horror game in about 100...
**Useful source sections:** The L4D model in four rules, The four-state cycle, A Roblox version.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Horror Tension Director - Intensity, Build Up, Peak and Relax, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Horror Tension Director - Intensity, Build Up, Peak and Relax and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Horror Tension Director - Intensity, Build Up, Peak and Relax|Horror Tension Director - Intensity, Build Up, Peak and Relax]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
