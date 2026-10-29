---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Reddit Scripting and Systems/Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox.md"
---
# Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox — Development Guide

New practical guidance for [[40 Community Resources/Reddit Scripting and Systems/Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox|Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The 2026 "Touched fires way before it touches" thread lists the alternatives people should use instead: `GetPartBoundsInBox`, `GetPartBoundsInRadius`, `GetPartsInPart`, `Raycast`, `Shapecast`, `Spherecast`, run on a RunService event during the swing. Touched is unreliable for fast-moving parts, and network travel time still applies even on the server (@ChiDj123).
**Useful source sections:** What changed, Why not .Touched for swords?, Own swing-window sketch with a blockcast.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Reddit Scripting and Systems/Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox|Melee Hitbox Modules - RaycastHitbox to ShapecastHitbox]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
