---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/Performance Optimization/Scene Analysis.md"
---
# Scene Analysis — Development Guide

New practical guidance for [[30 Official Roblox Docs/Performance Optimization/Scene Analysis|Scene Analysis]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Use the Scene Analysis tool to identify and resolve performance issues in your game. Check script memory, unparented instances, audio memory, animation memory, the instance composition view, and the extended scene triangle breakdown.
**Useful source sections:** Enable Scene Analysis, Use Scene Analysis, Modes.

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Scene Analysis, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Scene Analysis and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/Performance Optimization/Scene Analysis|Scene Analysis]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://create.roblox.com/docs/performance-optimization/scene-analysis

> Consult the linked official reference for current API signatures and platform constraints.
