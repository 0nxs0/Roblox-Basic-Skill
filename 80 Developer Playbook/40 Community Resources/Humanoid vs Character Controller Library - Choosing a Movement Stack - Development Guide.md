---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Characters Avatars and UGC/Humanoid vs Character Controller Library - Choosing a Movement Stack.md"
---
# Humanoid vs Character Controller Library - Choosing a Movement Stack — Development Guide

New practical guidance for [[40 Community Resources/Characters Avatars and UGC/Humanoid vs Character Controller Library - Choosing a Movement Stack|Humanoid vs Character Controller Library - Choosing a Movement Stack]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In 2026 a Roblox character can move three ways. Community reactions to the CCL release are already in Character Controller Library - Community First Impressions; this note compares the architectures so you can pick one.
**Useful source sections:** The three stacks, How the CCL thinks, Enabling.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For Humanoid vs Character Controller Library - Choosing a Movement Stack, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using Humanoid vs Character Controller Library - Choosing a Movement Stack and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Characters Avatars and UGC/Humanoid vs Character Controller Library - Choosing a Movement Stack|Humanoid vs Character Controller Library - Choosing a Movement Stack]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
