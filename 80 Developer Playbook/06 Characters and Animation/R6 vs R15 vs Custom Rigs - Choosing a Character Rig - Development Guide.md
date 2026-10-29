---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Deep Dives/R6 vs R15 vs Custom Rigs - Choosing a Character Rig.md"
---
# R6 vs R15 vs Custom Rigs - Choosing a Character Rig — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Deep Dives/R6 vs R15 vs Custom Rigs - Choosing a Character Rig|R6 vs R15 vs Custom Rigs - Choosing a Character Rig]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A fifth path sits between R15 and custom: a custom humanoid with Adaptive Animation. You import your own humanoid-shaped rig with Rig Type = Custom, then use the Avatar tab's Adaptive Animation tools to create a `HumanoidRigDescription` (and `DigitsRigDescription` per hand), map at least the 15 standard joints and enforce a T-pose. After that, the docs state the character can play back any R15 animation. This is...
**Useful source sections:** 1. The four real options in 2026, 2. Decision guide, 3. The R6-to-R15 adapter (`AvatarUnificationMode`).

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For R6 vs R15 vs Custom Rigs - Choosing a Character Rig, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using R6 vs R15 vs Custom Rigs - Choosing a Character Rig and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Deep Dives/R6 vs R15 vs Custom Rigs - Choosing a Character Rig|R6 vs R15 vs Custom Rigs - Choosing a Character Rig]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
