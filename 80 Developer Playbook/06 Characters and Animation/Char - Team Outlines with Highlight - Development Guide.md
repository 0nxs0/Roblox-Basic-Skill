---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Char - Team Outlines with Highlight.md"
---
# Char - Team Outlines with Highlight — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Char - Team Outlines with Highlight|Char - Team Outlines with Highlight]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Outlines answer "where is my squad?" in shooters, co-op horror and hide-and-seek, and they mark the target, the carrier or the downed player. The `Highlight` instance draws an outline plus an interior fill around a `Model` or `BasePart`, optionally through walls. The trap is visibility: a server-created highlight is seen by everyone, including enemies, which turns a team aid into a wallhack.
**Useful source sections:** The instance in one table, Client-only team outlines (the safe pattern), Design rules.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Char - Team Outlines with Highlight, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Char - Team Outlines with Highlight and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Char - Team Outlines with Highlight|Char - Team Outlines with Highlight]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
