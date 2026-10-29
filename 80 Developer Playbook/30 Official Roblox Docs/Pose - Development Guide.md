---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/API Reference/Classes/Pose.md"
---
# Pose — Development Guide

New practical guidance for [[30 Official Roblox Docs/API Reference/Classes/Pose|Pose]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Holds the `CFrame` applied to the `Motor6D` connected to its associated `BasePart`. The part which is controlled depends on the name of the Pose.
**Useful source sections:** Description, Poses, joints and hierarchy, Pose CFrame.

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Pose, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Pose and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/API Reference/Classes/Pose|Pose]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://create.roblox.com/docs/reference/engine/classes/Pose

> Consult the linked official reference for current API signatures and platform constraints.
