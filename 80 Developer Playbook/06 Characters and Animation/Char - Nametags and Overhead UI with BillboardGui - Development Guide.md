---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Char - Nametags and Overhead UI with BillboardGui.md"
---
# Char - Nametags and Overhead UI with BillboardGui — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Char - Nametags and Overhead UI with BillboardGui|Char - Nametags and Overhead UI with BillboardGui]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Overhead UI tells players who is who: names, titles, ranks, team colour, health, "typing" or "downed" icons. The built-in Humanoid name and health bar are plain and hard to style, so most games hide them and attach a `BillboardGui` to the head. Done badly, nametags clutter the screen, show through walls, scale into giant blocks at distance, or display unfiltered text.
**Useful source sections:** Hide the default display, Build the tag, Text safety.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Char - Nametags and Overhead UI with BillboardGui, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Char - Nametags and Overhead UI with BillboardGui and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Char - Nametags and Overhead UI with BillboardGui|Char - Nametags and Overhead UI with BillboardGui]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
