---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Designing Levels for NPC Navigation - Costs, Modifiers and Links.md"
---
# Designing Levels for NPC Navigation - Costs, Modifiers and Links — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Designing Levels for NPC Navigation - Costs, Modifiers and Links|Designing Levels for NPC Navigation - Costs, Modifiers and Links]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most NPC pathing bugs are level bugs: a doorway 0.2 studs too narrow for the agent radius, a decorative fence that splits the navmesh, a shortcut through lava because nothing told the agent it was bad. Roblox gives level designers three tools to shape where NPCs walk without touching AI code: material costs, PathfindingModifier regions, and PathfindingLink connections. This note is the level designer's checklist...
**Useful source sections:** Step 0: see the navmesh, Step 1: agent sizes decide your geometry, Step 2: material costs for preferences.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Designing Levels for NPC Navigation - Costs, Modifiers and Links, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Designing Levels for NPC Navigation - Costs, Modifiers and Links and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Designing Levels for NPC Navigation - Costs, Modifiers and Links|Designing Levels for NPC Navigation - Costs, Modifiers and Links]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
