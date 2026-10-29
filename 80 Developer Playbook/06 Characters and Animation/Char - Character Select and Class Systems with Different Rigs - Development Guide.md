---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Char - Character Select and Class Systems with Different Rigs.md"
---
# Char - Character Select and Class Systems with Different Rigs — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Char - Character Select and Class Systems with Different Rigs|Char - Character Select and Class Systems with Different Rigs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Hero shooters, asymmetric horror (survivors vs killer) and class RPGs all start with a select screen, then spawn the player as a rig that may not even be their avatar: a different size, different animations, different abilities. The mistakes are predictable: the client decides the class (exploitable), the player spawns once as their avatar and then "pops" into the class rig, or animations break because the class...
**Useful source sections:** Flow that holds up, Two kinds of class, Class data in one place.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Char - Character Select and Class Systems with Different Rigs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Char - Character Select and Class Systems with Different Rigs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Char - Character Select and Class Systems with Different Rigs|Char - Character Select and Class Systems with Different Rigs]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
