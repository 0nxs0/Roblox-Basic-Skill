---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Landing Animations by Fall Height - Soft, Hard and Roll.md"
---
# Anim - Landing Animations by Fall Height - Soft, Hard and Roll — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Landing Animations by Fall Height - Soft, Hard and Roll|Anim - Landing Animations by Fall Height - Soft, Hard and Roll]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The default Roblox character lands from a 2-stud hop and a 60-stud drop the same way: it just goes back to running. Matching the landing to the fall sells weight more than any other movement detail, and it gives you a natural place for fall damage, camera dip and dust VFX. The pattern DevForum threads converge on: record where the fall started, measure on `Landed`, pick a clip by bucket.
**Useful source sections:** Measure the fall: height or impact speed, Buckets, Code (LocalScript in StarterCharacterScripts).

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Landing Animations by Fall Height - Soft, Hard and Roll, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Landing Animations by Fall Height - Soft, Hard and Roll and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Landing Animations by Fall Height - Soft, Hard and Roll|Anim - Landing Animations by Fall Height - Soft, Hard and Roll]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
