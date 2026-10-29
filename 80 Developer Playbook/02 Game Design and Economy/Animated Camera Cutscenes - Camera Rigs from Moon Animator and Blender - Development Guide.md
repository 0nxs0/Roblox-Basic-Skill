---
kind: development-companion
category: "02 Game Design and Economy"
source-note: "02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender.md"
---
# Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender — Development Guide

New practical guidance for [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender|Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Scripted camera paths (waypoints plus splines, see Cutscene Cameras - Spline Paths, Letterbox and Skip) are great for fly-throughs. They are poor at handheld, character-driven shots: a camera that stumbles with a running survivor, whips toward a scream, or tracks a monster's lunge frame by frame. For those, many Roblox developers animate the camera like a character: keyframe a part in an animation tool, then make...
**Useful source sections:** The core trick: camera follows an animated part, Tool paths, FOV, cuts and shake.

## Apply it
Use this topic as part of **make fair, measurable player loops**.
- **Define the contract:** For Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map action, feedback, reward, and next choice; define cost, pacing, and a success measure.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check exploits, runaway rewards, and no-spend fairness.

## Validate before shipping
- **Expected path:** Build one small feature using Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test first play, repeat play, and edge-case balances.

## Connected work
- Source note: [[02 Game Design and Economy/Story Quests Cinematics/Community Knowledge/Story - Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender|Animated Camera Cutscenes - Camera Rigs from Moon Animator and Blender]]
- Category hub: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy development hub]]
- Related disciplines: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
