---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Free VFX and FX/Fixing Black Outlines on Particle Textures.md"
---
# Fixing Black Outlines on Particle Textures — Development Guide

New practical guidance for [[40 Community Resources/Free VFX and FX/Fixing Black Outlines on Particle Textures|Fixing Black Outlines on Particle Textures]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A Roblox staff member (neutrinostack) explained in a Nov 2023 DevForum thread that this is a limitation of bilinear filtering, not a bug. Fully transparent pixels still store a colour, and most editors save them as black. When Roblox scales the texture, edge pixels blend with those hidden black pixels. Pre-multiplied alpha would avoid it, but Roblox does not support it.
**Useful source sections:** Why it happens, Fixes (best first), Quick check before upload.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For Fixing Black Outlines on Particle Textures, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using Fixing Black Outlines on Particle Textures and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Free VFX and FX/Fixing Black Outlines on Particle Textures|Fixing Black Outlines on Particle Textures]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
