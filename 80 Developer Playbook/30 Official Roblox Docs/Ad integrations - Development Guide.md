---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/Production/Promotion/Ad integrations.md"
---
# Ad integrations — Development Guide

New practical guidance for [[30 Official Roblox Docs/Production/Promotion/Ad integrations|Ad integrations]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Ad integrations are advertisements that aren't part of Roblox's built-in ad products and that promote products or services outside of a game or off Roblox.
**Useful source sections:** Is your content advertising?, Requirements, Submit your ad integration.

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Ad integrations, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Ad integrations and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/Production/Promotion/Ad integrations|Ad integrations]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://create.roblox.com/docs/production/promotion/ad-integrations

> Consult the linked official reference for current API signatures and platform constraints.
