---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Fusion 0.3 - Scopes, State and Reactive UI.md"
---
# Fusion 0.3 - Scopes, State and Reactive UI — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Fusion 0.3 - Scopes, State and Reactive UI|Fusion 0.3 - Scopes, State and Reactive UI]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Fusion is a reactive UI library made for Roblox and Luau: you declare what the UI should look like for a given state, and Fusion updates instance properties when that state changes. Compared with hand-wiring `.Changed` events, you stop writing "remember to also update label X" code. Version 0.3 introduced scopes, which is the part most older tutorials get wrong, so this note focuses on it. For choosing between...
**Useful source sections:** Scopes: the 0.3 idea, State objects, Building instances.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Fusion 0.3 - Scopes, State and Reactive UI, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Fusion 0.3 - Scopes, State and Reactive UI and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Fusion 0.3 - Scopes, State and Reactive UI|Fusion 0.3 - Scopes, State and Reactive UI]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
