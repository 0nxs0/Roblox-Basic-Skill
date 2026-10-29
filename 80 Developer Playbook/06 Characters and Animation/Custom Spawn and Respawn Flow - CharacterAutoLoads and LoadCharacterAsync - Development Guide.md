---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync.md"
---
# Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync|Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The default flow (join, spawn at a SpawnLocation, die, wait 5 seconds, respawn) suits obbies and hangouts. Round-based games, class selection screens, death cams and "spectate until next round" all need you to take control of when characters appear. The switch is `Players.CharacterAutoLoads`; after that, your server code decides when to call `Player:LoadCharacterAsync()` and with what appearance.
**Useful source sections:** The knobs, A round-based skeleton, Choosing where they spawn.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync|Custom Spawn and Respawn Flow - CharacterAutoLoads and LoadCharacterAsync]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
