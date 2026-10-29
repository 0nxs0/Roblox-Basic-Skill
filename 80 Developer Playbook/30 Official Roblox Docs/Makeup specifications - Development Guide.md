---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/Avatar/Makeup/Makeup specifications.md"
---
# Makeup specifications — Development Guide

New practical guidance for [[30 Official Roblox Docs/Avatar/Makeup/Makeup specifications|Makeup specifications]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Makeup is a cosmetic look made up of multiple facial textures and optional eyebrow and eyelashes.
**Useful source sections:** General, Decals and textures, Eyebrows and eyelashes.

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Makeup specifications, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Makeup specifications and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/Avatar/Makeup/Makeup specifications|Makeup specifications]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://create.roblox.com/docs/avatar/makeup/specifications

> Consult the linked official reference for current API signatures and platform constraints.
