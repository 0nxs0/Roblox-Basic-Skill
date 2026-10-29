---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/GoodSignal - Pure-Luau Signals and Their Caveats.md"
---
# GoodSignal - Pure-Luau Signals and Their Caveats — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/GoodSignal - Pure-Luau Signals and Their Caveats|GoodSignal - Pure-Luau Signals and Their Caveats]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Custom events ("signals") let modules talk without knowing each other: `Inventory.ItemAdded:Connect(...)`. The old way was wrapping a BindableEvent, which copies arguments (tables lose identity and metatables) and is slower. GoodSignal is a small pure-Luau signal that keeps arguments by reference and is the base many other signal libraries copy. This note explains how it works, what it costs and where it bites....
**Useful source sections:** API, Why it is fast, Caveats you will hit.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For GoodSignal - Pure-Luau Signals and Their Caveats, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using GoodSignal - Pure-Luau Signals and Their Caveats and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/GoodSignal - Pure-Luau Signals and Their Caveats|GoodSignal - Pure-Luau Signals and Their Caveats]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
