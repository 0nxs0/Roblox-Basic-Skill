---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/NPC Animation at Scale - Where to Play Tracks and Animator LOD.md"
---
# NPC Animation at Scale - Where to Play Tracks and Animator LOD — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/NPC Animation at Scale - Where to Play Tracks and Animator LOD|NPC Animation at Scale - Where to Play Tracks and Animator LOD]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Wave shooters, zombie games and tower defense games can have 50-200 animated rigs alive at once. Animation is often the hidden cost: every `Animator` evaluates its tracks every frame on every client that can see it. Getting the "who plays the track" rule right, and letting the engine's animator LOD do its job, is the difference between a stable 60 FPS and a slideshow on phones.
**Useful source sections:** Rule 1: who plays the animation, Rule 2: load once, reuse forever, Rule 3: let animator LOD work.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For NPC Animation at Scale - Where to Play Tracks and Animator LOD, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using NPC Animation at Scale - Where to Play Tracks and Animator LOD and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/NPC Animation at Scale - Where to Play Tracks and Animator LOD|NPC Animation at Scale - Where to Play Tracks and Animator LOD]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
