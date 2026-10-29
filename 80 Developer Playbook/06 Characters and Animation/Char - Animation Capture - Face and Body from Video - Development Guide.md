---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Char - Animation Capture - Face and Body from Video.md"
---
# Char - Animation Capture - Face and Body from Video — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Char - Animation Capture - Face and Body from Video|Char - Animation Capture - Face and Body from Video]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox Studio's Animation Capture turns video into keyframes inside the Animation Editor, with no mocap suit and no external tool. For small teams this is the fastest route to believable emotes, cutscene acting, NPC idles and reaction clips. It is not a replacement for hand-keyed combat animation, but it is an excellent first pass you then clean up.
**Useful source sections:** Two tools, Face capture workflow, Body capture workflow.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Char - Animation Capture - Face and Body from Video, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Char - Animation Capture - Face and Body from Video and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Char - Animation Capture - Face and Body from Video|Char - Animation Capture - Face and Body from Video]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
