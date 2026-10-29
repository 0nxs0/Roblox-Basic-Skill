---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic.md"
---
# Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic|Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Until recently every Roblox game built its animation logic in Luau: load tracks, play and stop them, adjust weights by speed. Studio now has an Animation Graph Editor (Avatar tab > Graph Editor): a node-based tool that builds blend trees and state machines into a published `AnimationGraphDefinition` asset, loaded onto an `Animator` like a normal animation and driven by parameters. This note helps you decide which...
**Useful source sections:** How the graph is driven, Decision table, A good hybrid.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic|Animation Graph Editor vs Scripted Tracks - Choosing Your Animation Logic]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
