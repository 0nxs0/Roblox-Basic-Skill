---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export.md"
---
# Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export|Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Mocap, video capture and retargeted clips arrive with a key on every frame for every bone. They play fine, but they are miserable to edit in the Roblox Animation Editor: moving one arm means dragging 60 keys, a timing change means re-baking, and the dope sheet is a solid wall. Reducing keys before export turns a capture into something you can actually polish. This note is the Blender side of that step; the...
**Useful source sections:** When to reduce, when not to, Workflow in Blender, Export.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export|Anim - Keyframe Reduction for Baked Mocap - Blender Decimate Before Export]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
