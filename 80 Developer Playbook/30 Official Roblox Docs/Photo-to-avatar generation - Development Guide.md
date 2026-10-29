---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/Avatar/Photo-to-avatar generation.md"
---
# Photo-to-avatar generation — Development Guide

New practical guidance for [[30 Official Roblox Docs/Avatar/Photo-to-avatar generation|Photo-to-avatar generation]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Explains how to use AvatarCreationService AvatarGeneration APIs to prompt users to generate Avatars from photos in a game.
**Useful source sections:** Request an avatar generation session, Prompt selfie and generate 2D preview, Generate the avatar.

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Photo-to-avatar generation, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Photo-to-avatar generation and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/Avatar/Photo-to-avatar generation|Photo-to-avatar generation]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://create.roblox.com/docs/avatar/avatar-generation

> Consult the linked official reference for current API signatures and platform constraints.
