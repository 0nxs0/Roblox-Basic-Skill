---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Characters Avatars and UGC/UGC Validation Failures - Triage by Error Type.md"
---
# UGC Validation Failures - Triage by Error Type — Development Guide

New practical guidance for [[40 Community Resources/Characters Avatars and UGC/UGC Validation Failures - Triage by Error Type|UGC Validation Failures - Triage by Error Type]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The official UGC validation system page lists every error. This note groups them by where you fix them, so you know whether to open Blender or stay in Studio. Validation runs on Studio upload and on in-game creation through AvatarCreationService. In-game-only assets do not need to pass, but the checks are still a good debug tool.
**Useful source sections:** Fix in Blender (geometry, UVs, cages, rig), Fix in Studio (hierarchy, properties, attachments), Order of operations.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For UGC Validation Failures - Triage by Error Type, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using UGC Validation Failures - Triage by Error Type and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Characters Avatars and UGC/UGC Validation Failures - Triage by Error Type|UGC Validation Failures - Triage by Error Type]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
