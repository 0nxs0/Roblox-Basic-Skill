---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values.md"
---
# Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values|Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Grow bigger as you eat" simulators, shrink potions, boss transformations and kid/adult NPC variants all need characters resized while the game runs. Roblox gives two very different tools. `Model:ScaleTo()` uniformly scales everything in a model (parts, joints, attachments, particles); the R15 body scale values (`HeightScale`, `WidthScale`, `DepthScale`, `HeadScale` in a `HumanoidDescription`) reshape the avatar...
**Useful source sections:** Model:ScaleTo in short, Body scale values in short, Which to use.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values|Resizing Characters at Runtime - Model ScaleTo vs Body Scale Values]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
