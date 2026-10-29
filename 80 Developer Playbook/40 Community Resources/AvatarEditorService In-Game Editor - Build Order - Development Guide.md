---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Characters Avatars and UGC/AvatarEditorService In-Game Editor - Build Order.md"
---
# AvatarEditorService In-Game Editor - Build Order — Development Guide

New practical guidance for [[40 Community Resources/Characters Avatars and UGC/AvatarEditorService In-Game Editor - Build Order|AvatarEditorService In-Game Editor - Build Order]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`AvatarEditorService` (AES) lets a game read a player's inventory, search the Marketplace, save avatars and outfits, and pair with `MarketplaceService` for purchases. In-game sales of other creators' items pay the game owner 40% of the price (creator 30%, Roblox 30%), which is why catalog and dress-up games exist.
**Useful source sections:** Build it in this order, Throttling, Original client search helper with cache and debounce.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For AvatarEditorService In-Game Editor - Build Order, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using AvatarEditorService In-Game Editor - Build Order and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Characters Avatars and UGC/AvatarEditorService In-Game Editor - Build Order|AvatarEditorService In-Game Editor - Build Order]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
