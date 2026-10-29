---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path.md"
---
# Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path|Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A vault is the move where the character plants a hand on a low wall, crate or railing and swings over it without stopping. It keeps chases and parkour flowing where a jump would clip the edge and kill momentum. The ledge-grab recipe covers tall edges you hang from; this note is for waist-high obstacles (roughly 1.5-4 studs on a default-size R15 character) that you cross in one smooth move.
**Useful source sections:** Detect with three rays, Move the root on a path, let the clip sell it, Animation tips.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path|Anim - Vaulting Low Obstacles - Three-Ray Check, Clip Sync and Root Path]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
