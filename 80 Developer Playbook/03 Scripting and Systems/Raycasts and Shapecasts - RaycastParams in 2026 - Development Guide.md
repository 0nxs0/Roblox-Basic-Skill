---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Math Geometry/Community Knowledge/Raycasts and Shapecasts - RaycastParams in 2026.md"
---
# Raycasts and Shapecasts - RaycastParams in 2026 — Development Guide

New practical guidance for [[03 Scripting and Systems/Math Geometry/Community Knowledge/Raycasts and Shapecasts - RaycastParams in 2026|Raycasts and Shapecasts - RaycastParams in 2026]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Spatial queries are how games answer "what is there?": bullets, line of sight, ground checks, melee sweeps, placement validation, camera collision. Roblox now offers four cast shapes and a RaycastParams object that gained new fields (`ExcludeInstances`, `IncludeInstances`, `Margin`, `SizeGradient`). Most older tutorials only know `FilterDescendantsInstances`. This note is the current picture, taken from the API...
**Useful source sections:** The four casts, RaycastParams fields, Recipes (own code).

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Raycasts and Shapecasts - RaycastParams in 2026, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Raycasts and Shapecasts - RaycastParams in 2026 and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Math Geometry/Community Knowledge/Raycasts and Shapecasts - RaycastParams in 2026|Raycasts and Shapecasts - RaycastParams in 2026]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
