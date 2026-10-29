---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync.md"
---
# Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync|Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A paired animation is one moment played by two characters at once: a handshake or high five in a social hangout, a grab-and-throw in a fighting game, a takedown finisher, a hug emote. It only works if both characters stand in exactly the right spot relative to each other and both clips start on the same frame. DevForum threads agree on the core idea (animate both rigs together, then lock their relative position)...
**Useful source sections:** Author both clips together, Play them in sync (server), Approach and alignment.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync|Anim - Paired Animations - Handshakes, Grabs and Finishers in Sync]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
