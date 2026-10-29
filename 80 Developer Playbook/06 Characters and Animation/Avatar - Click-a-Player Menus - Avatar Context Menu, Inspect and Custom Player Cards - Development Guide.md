---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards.md"
---
# Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards|Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Hangouts, roleplay and trading games live on "click someone, do something with them": trade, invite to party, inspect outfit, wave. Roblox gives you two built-in pieces (the Avatar Context Menu and the Avatar Inspect Menu) and you can build a third (your own player card). This note is the decision guide and the safe wiring; the official pages list every option.
**Useful source sections:** Which one, ACM wiring (client), Inspect what they are wearing now.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards|Avatar - Click-a-Player Menus - Avatar Context Menu, Inspect and Custom Player Cards]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
