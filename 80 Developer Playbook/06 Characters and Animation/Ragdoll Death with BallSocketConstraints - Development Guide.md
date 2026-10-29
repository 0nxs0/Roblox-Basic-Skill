---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Ragdoll Death with BallSocketConstraints.md"
---
# Ragdoll Death with BallSocketConstraints — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Ragdoll Death with BallSocketConstraints|Ragdoll Death with BallSocketConstraints]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
By default a Roblox character that dies simply falls apart: `Humanoid.BreakJointsOnDeath` is `true`, so every joint is destroyed and the limbs scatter. A ragdoll keeps the body connected but floppy, which reads far better for combat, horror and physics games. The standard community method is to swap each `Motor6D` for a `BallSocketConstraint` at the moment of death (or knock-down), and it works for both R6 and R15.
**Useful source sections:** The core recipe, Limits per joint (starting values), Knock-down without death.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Ragdoll Death with BallSocketConstraints, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Ragdoll Death with BallSocketConstraints and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Ragdoll Death with BallSocketConstraints|Ragdoll Death with BallSocketConstraints]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
