---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets.md"
---
# Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets|Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every Roblox character makes the same jump, land, run, swim and death sounds out of the box. A robot class that lands with a metal clank, a monster morph that growls when it dies, or a horror game where the default cartoony jump sound is gone: these all need you to take over the character sound script. There are two supported hooks and one common community fork.
**Useful source sections:** The three ways in, Muting one sound properly, Per-character sound sets (morphs and classes).

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets|Avatar - Custom Character Sounds - Forking RbxCharacterSounds and Per-Character Sound Sets]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
