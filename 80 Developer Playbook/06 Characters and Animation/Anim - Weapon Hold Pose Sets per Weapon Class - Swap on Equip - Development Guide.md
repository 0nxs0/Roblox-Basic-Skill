---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip.md"
---
# Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip|Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A pistol, a rifle, a greatsword and a flashlight should not all be held with the default "arm stuck out" tool pose. Games that feel finished give each weapon class its own hold pose set (idle hold, walk hold, aim, sprint-lower), and every weapon of that class shares the set. This note is about organising and swapping those sets; the grip joint itself is covered in the Motor6D grips note.
**Useful source sections:** Classes, not weapons, How the layers stack, The tool slot in Animate.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip|Anim - Weapon Hold Pose Sets per Weapon Class - Swap on Equip]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
