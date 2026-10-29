---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Char - Death Animations and Respawn Timing.md"
---
# Char - Death Animations and Respawn Timing — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Char - Death Animations and Respawn Timing|Char - Death Animations and Respawn Timing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Ragdolls are not the only good death. Stylised, horror and story games often want an authored fall: the character clutches, drops to its knees and lands in a pose you designed. That needs three things working together: keep the joints alive, play a high-priority track that holds its last frame, and time the respawn so the pose is actually seen. The ragdoll version is covered in Ragdoll Death with...
**Useful source sections:** Step by step, Things that break it, Checklist.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Char - Death Animations and Respawn Timing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Char - Death Animations and Respawn Timing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Char - Death Animations and Respawn Timing|Char - Death Animations and Respawn Timing]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
