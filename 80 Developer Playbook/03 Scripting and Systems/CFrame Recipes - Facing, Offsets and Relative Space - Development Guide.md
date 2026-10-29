---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Math Geometry/Community Knowledge/CFrame Recipes - Facing, Offsets and Relative Space.md"
---
# CFrame Recipes - Facing, Offsets and Relative Space — Development Guide

New practical guidance for [[03 Scripting and Systems/Math Geometry/Community Knowledge/CFrame Recipes - Facing, Offsets and Relative Space|CFrame Recipes - Facing, Offsets and Relative Space]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A `CFrame` is a position plus a rotation (a 3x4 matrix). Nearly every placement problem in Roblox (aim a turret, spawn a projectile at the muzzle, keep a pet behind the player, snap a build-mode block, orbit a camera) is a two-line CFrame recipe once you know which operation to use. This note collects the ones that come up most, using only constructors and methods listed in the current API reference.
**Useful source sections:** The two rules, Facing and aiming, Offsets and relative space.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For CFrame Recipes - Facing, Offsets and Relative Space, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using CFrame Recipes - Facing, Offsets and Relative Space and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Math Geometry/Community Knowledge/CFrame Recipes - Facing, Offsets and Relative Space|CFrame Recipes - Facing, Offsets and Relative Space]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
