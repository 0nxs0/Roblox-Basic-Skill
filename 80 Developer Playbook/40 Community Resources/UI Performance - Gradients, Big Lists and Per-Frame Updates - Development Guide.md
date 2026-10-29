---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Performance and Security/UI Performance - Gradients, Big Lists and Per-Frame Updates.md"
---
# UI Performance - Gradients, Big Lists and Per-Frame Updates — Development Guide

New practical guidance for [[40 Community Resources/Performance and Security/UI Performance - Gradients, Big Lists and Per-Frame Updates|UI Performance - Gradients, Big Lists and Per-Frame Updates]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
UI rarely shows up in profiling until a shop with 800 items or an animated gradient HUD drops low-end phones below 30 FPS. Three causes come up again and again: expensive gradient animation, huge lists, and writing UI properties every frame.
**Useful source sections:** 1. UIGradient rules (Creator Hub, Performance Considerations), 2. Big lists: only show what's on screen, 3. Per-frame writes.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For UI Performance - Gradients, Big Lists and Per-Frame Updates, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using UI Performance - Gradients, Big Lists and Per-Frame Updates and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Performance and Security/UI Performance - Gradients, Big Lists and Per-Frame Updates|UI Performance - Gradients, Big Lists and Per-Frame Updates]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
