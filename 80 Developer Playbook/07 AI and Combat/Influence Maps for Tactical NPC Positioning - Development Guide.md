---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Influence Maps for Tactical NPC Positioning.md"
---
# Influence Maps for Tactical NPC Positioning — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Influence Maps for Tactical NPC Positioning|Influence Maps for Tactical NPC Positioning]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Where should this NPC stand?" is harder than "how does it get there". Ranged enemies that stand in the open, guards that all cluster at one door, and zombies that ignore the gap where players are weakest all come from NPCs choosing positions with no picture of the battlefield. An influence map is that picture: a grid where every friendly and hostile unit spreads a value that fades with distance. Alex...
**Useful source sections:** Building one, Using it for decisions, Memory layer.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Influence Maps for Tactical NPC Positioning, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Influence Maps for Tactical NPC Positioning and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Influence Maps for Tactical NPC Positioning|Influence Maps for Tactical NPC Positioning]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
