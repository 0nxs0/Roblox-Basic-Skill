---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/First-Person Viewmodels - Arms Rig, Camera Binding and Sway.md"
---
# First-Person Viewmodels - Arms Rig, Camera Binding and Sway — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/First-Person Viewmodels - Arms Rig, Camera Binding and Sway|First-Person Viewmodels - Arms Rig, Camera Binding and Sway]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every serious Roblox shooter hides the real character in first person and draws a separate, client-only "viewmodel": a pair of arms plus the weapon, glued to the camera. This lets you animate reloads and inspects at close range with exaggerated poses, a tighter field of view feel and no clipping into walls, while other players still see your normal third-person character. The pattern is old and stable on the...
**Useful source sections:** Rig layout, Binding to the camera, Hiding the real body.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For First-Person Viewmodels - Arms Rig, Camera Binding and Sway, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using First-Person Viewmodels - Arms Rig, Camera Binding and Sway and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/First-Person Viewmodels - Arms Rig, Camera Binding and Sway|First-Person Viewmodels - Arms Rig, Camera Binding and Sway]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
