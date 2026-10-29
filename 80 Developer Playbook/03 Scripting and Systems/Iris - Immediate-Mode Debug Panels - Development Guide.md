---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Iris - Immediate-Mode Debug Panels.md"
---
# Iris - Immediate-Mode Debug Panels — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Iris - Immediate-Mode Debug Panels|Iris - Immediate-Mode Debug Panels]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Iris is an immediate-mode GUI library for Roblox modelled on Dear ImGui. Instead of building a ScreenGui and wiring events, you call widget functions every frame and Iris creates, updates and removes the instances for you. That makes it the fastest way to build developer tools: tuning sliders for weapon recoil, a live view of a state machine, a spawn menu for testers, a network stats overlay. It is not meant for...
**Useful source sections:** Basic shape, Good uses in a Roblox project, Shipping safely.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Iris - Immediate-Mode Debug Panels, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Iris - Immediate-Mode Debug Panels and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Iris - Immediate-Mode Debug Panels|Iris - Immediate-Mode Debug Panels]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
