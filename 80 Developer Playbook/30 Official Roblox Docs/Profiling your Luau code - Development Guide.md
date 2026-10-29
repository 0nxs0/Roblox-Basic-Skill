---
kind: development-companion
category: "30 Official Roblox Docs"
source-note: "30 Official Roblox Docs/Luau Language/Guides/Profiling your Luau code.md"
---
# Profiling your Luau code — Development Guide

New practical guidance for [[30 Official Roblox Docs/Luau Language/Guides/Profiling your Luau code|Profiling your Luau code]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
One of the main goals of Luau is to enable high performance code. To help with that goal, we are relentlessly optimizing the compiler and runtime - but ultimately, performance of their code is in developers' hands, and is a combination of good algorithm design and implementation that adheres to the strengths of the language. To help write efficient code, Luau provides a built-in profiler that samples the...

## Apply it
Use this topic as part of **turn API references into tested Studio features**.
- **Define the contract:** For Profiling your Luau code, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Check the linked reference for current signatures and constraints; build the smallest feature using it.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Respect client-server boundaries, permissions, lifecycle, and deprecation notes.

## Validate before shipping
- **Expected path:** Build one small feature using Profiling your Luau code and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test normal use, invalid inputs, ownership, cleanup, and target setup.

## Connected work
- Source note: [[30 Official Roblox Docs/Luau Language/Guides/Profiling your Luau code|Profiling your Luau code]]
- Category hub: [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
- Source URL: https://luau.org/guides/profile

> Consult the linked official reference for current API signatures and platform constraints.
