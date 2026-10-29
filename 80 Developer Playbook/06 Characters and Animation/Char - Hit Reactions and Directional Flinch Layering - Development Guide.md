---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Char - Hit Reactions and Directional Flinch Layering.md"
---
# Char - Hit Reactions and Directional Flinch Layering — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Char - Hit Reactions and Directional Flinch Layering|Char - Hit Reactions and Directional Flinch Layering]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A hit that plays no reaction feels like it missed. Good combat games answer every confirmed hit with three things inside about 100 ms: a short flinch on the victim, a pause or "hit-stop" on the attacker, and a sound/VFX. On Roblox the flinch is just another `AnimationTrack`, but it has to sit on top of locomotion without stopping it and without letting enemies stun-lock each other.
**Useful source sections:** Build a small reaction set, Pick the direction, Play it right.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Char - Hit Reactions and Directional Flinch Layering, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Char - Hit Reactions and Directional Flinch Layering and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Char - Hit Reactions and Directional Flinch Layering|Char - Hit Reactions and Directional Flinch Layering]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
