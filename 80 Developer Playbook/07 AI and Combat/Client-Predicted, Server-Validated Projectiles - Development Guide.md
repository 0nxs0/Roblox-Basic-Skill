---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Deep Dives/Client-Predicted, Server-Validated Projectiles.md"
---
# Client-Predicted, Server-Validated Projectiles — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Deep Dives/Client-Predicted, Server-Validated Projectiles|Client-Predicted, Server-Validated Projectiles]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
export type Proj = { id: number, position: Vector3, velocity: Vector3, gravity: Vector3, -- e.g. Vector3.new(0, -workspace.Gravity 0.5, 0) for a lobbed shot radius: number, -- 0 = raycast, > 0 = spherecast maxDistance: number, traveled: number, params: RaycastParams, alive: boolean, }
**Useful source sections:** 1. Architecture, 2. The shared simulation step, 3. Shooter client.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Client-Predicted, Server-Validated Projectiles, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Client-Predicted, Server-Validated Projectiles and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Deep Dives/Client-Predicted, Server-Validated Projectiles|Client-Predicted, Server-Validated Projectiles]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
