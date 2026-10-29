---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Flow Fields for Large Hordes.md"
---
# Flow Fields for Large Hordes — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Flow Fields for Large Hordes|Flow Fields for Large Hordes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`PathfindingService` computes one path per request. With 150 zombies chasing the same player, that is 150 `ComputeAsync` calls every time the player moves, which is exactly how horde games tank server performance. Red Blob Games' tower-defense article explains the alternative: when many agents share a destination, run one search outward from the destination and store, for every tile, which way leads home. Every...
**Useful source sections:** How it works, Making it work in a Roblox game, Flow field vs PathfindingService.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Flow Fields for Large Hordes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Flow Fields for Large Hordes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Flow Fields for Large Hordes|Flow Fields for Large Hordes]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
