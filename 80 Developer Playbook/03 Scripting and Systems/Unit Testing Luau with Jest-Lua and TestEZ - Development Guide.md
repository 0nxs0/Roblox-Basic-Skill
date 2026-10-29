---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Deep Dives/Unit Testing Luau with Jest-Lua and TestEZ.md"
---
# Unit Testing Luau with Jest-Lua and TestEZ — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Deep Dives/Unit Testing Luau with Jest-Lua and TestEZ|Unit Testing Luau with Jest-Lua and TestEZ]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The vault's QA notes (Testing and QA Operating System, Full Test Matrix) cover manual and release testing. This note covers automated tests for Luau logic.
**Useful source sections:** 1. What to unit test (and what not to), 2. The two frameworks, 3. TestEZ: specs and runner.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Unit Testing Luau with Jest-Lua and TestEZ, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Unit Testing Luau with Jest-Lua and TestEZ and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Deep Dives/Unit Testing Luau with Jest-Lua and TestEZ|Unit Testing Luau with Jest-Lua and TestEZ]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
