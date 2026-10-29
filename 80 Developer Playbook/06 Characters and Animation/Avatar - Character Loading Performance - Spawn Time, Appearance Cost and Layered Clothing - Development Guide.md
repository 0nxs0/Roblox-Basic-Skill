---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing.md"
---
# Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing|Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"I joined and stood as a grey blob for five seconds" and "everyone hitches when a new player spawns" are both character-loading problems. A player's avatar is fetched, its meshes and textures downloaded, layered clothing wrapped onto the body, and only then does `CharacterAppearanceLoaded` fire. You cannot make Roblox's servers faster, but you control how much appearance you load, when gameplay waits for it, and...
**Useful source sections:** What costs time, Levers in order of impact, Do not block gameplay on appearance.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing|Avatar - Character Loading Performance - Spawn Time, Appearance Cost and Layered Clothing]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
