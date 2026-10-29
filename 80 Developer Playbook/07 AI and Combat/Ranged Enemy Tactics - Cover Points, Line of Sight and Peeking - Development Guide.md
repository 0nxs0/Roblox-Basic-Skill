---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking.md"
---
# Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking|Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A ranged enemy that stands still in the open and shoots is a target dummy; one that hides permanently is just annoying. Good shooter AI picks positions: somewhere it is protected from the player but can still shoot, moves between such positions, and peeks out on a rhythm the player can learn. Commercial engines do this with position queries (CryENGINE's Tactical Point System, Unreal's Environment Query System,...
**Useful source sections:** 1. Author cover points, 2. Score candidate points, 3. The cover loop.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking|Ranged Enemy Tactics - Cover Points, Line of Sight and Peeking]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
