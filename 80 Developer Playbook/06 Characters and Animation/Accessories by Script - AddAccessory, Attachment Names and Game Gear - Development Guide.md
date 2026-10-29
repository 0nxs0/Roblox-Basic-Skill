---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Accessories by Script - AddAccessory, Attachment Names and Game Gear.md"
---
# Accessories by Script - AddAccessory, Attachment Names and Game Gear — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Accessories by Script - AddAccessory, Attachment Names and Game Gear|Accessories by Script - AddAccessory, Attachment Names and Game Gear]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Helmets, backpacks, armour plates, quest hats and team badges are the bread and butter of character customization, and most of them should be plain `Accessory` instances added from the server. Using the accessory system (instead of welding random parts) means the item scales with the avatar, follows animations, survives `HumanoidDescription` changes predictably and can be removed in one call.
**Useful source sections:** How AddAccessory finds its spot, R15 attachment names to use, Building gear for your game.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Accessories by Script - AddAccessory, Attachment Names and Game Gear, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Accessories by Script - AddAccessory, Attachment Names and Game Gear and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Accessories by Script - AddAccessory, Attachment Names and Game Gear|Accessories by Script - AddAccessory, Attachment Names and Game Gear]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
