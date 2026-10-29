---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/Production/Publishing/Thumbnails.md"
---
# Thumbnails — Development Guide

New practical guidance for [[30 Official Roblox Docs/Production/Publishing/Thumbnails|Thumbnails]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Thumbnail images and videos appear on the Roblox home page and at the top of a game's detail page to showcase features and share information.
**Useful source sections:** Manage thumbnails, Free camera mode, Home page personalization.

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Thumbnails, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Thumbnails and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/Production/Publishing/Thumbnails|Thumbnails]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://create.roblox.com/docs/production/publishing/thumbnails

> Consult the linked official reference for current API signatures and platform constraints.
