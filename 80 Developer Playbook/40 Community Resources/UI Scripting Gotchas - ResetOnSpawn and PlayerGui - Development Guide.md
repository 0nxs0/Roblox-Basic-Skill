---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Reddit Scripting and Systems/UI Scripting Gotchas - ResetOnSpawn and PlayerGui.md"
---
# UI Scripting Gotchas - ResetOnSpawn and PlayerGui — Development Guide

New practical guidance for [[40 Community Resources/Reddit Scripting and Systems/UI Scripting Gotchas - ResetOnSpawn and PlayerGui|UI Scripting Gotchas - ResetOnSpawn and PlayerGui]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The UI bugs that eat beginners' evenings, with the fixes the community settled on.
**Useful source sections:** 1. Editing StarterGui instead of PlayerGui, 2. UI resets (and buttons die) on respawn, 3. "Do I need WaitForChild for my own GUI?".

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For UI Scripting Gotchas - ResetOnSpawn and PlayerGui, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using UI Scripting Gotchas - ResetOnSpawn and PlayerGui and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Reddit Scripting and Systems/UI Scripting Gotchas - ResetOnSpawn and PlayerGui|UI Scripting Gotchas - ResetOnSpawn and PlayerGui]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
