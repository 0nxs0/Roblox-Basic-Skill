---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/True First Person - Seeing Your Own Body with LocalTransparencyModifier.md"
---
# True First Person - Seeing Your Own Body with LocalTransparencyModifier — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/True First Person - Seeing Your Own Body with LocalTransparencyModifier|True First Person - Seeing Your Own Body with LocalTransparencyModifier]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
When the default camera zooms into first person, Roblox hides your whole character so the head does not block the view. Horror and immersive games often want the opposite: look down and see your legs, see your arms holding a flashlight. This "true first person" (or "body cam") look is done with one client-only property, `BasePart.LocalTransparencyModifier`, plus a camera offset so the head does not fill the screen.
**Useful source sections:** How the property works, What to keep hidden, Camera position.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For True First Person - Seeing Your Own Body with LocalTransparencyModifier, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using True First Person - Seeing Your Own Body with LocalTransparencyModifier and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/True First Person - Seeing Your Own Body with LocalTransparencyModifier|True First Person - Seeing Your Own Body with LocalTransparencyModifier]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
