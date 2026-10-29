---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/React-Lua on Roblox - Packages, Hooks and Roact Migration.md"
---
# React-Lua on Roblox - Packages, Hooks and Roact Migration — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/React-Lua on Roblox - Packages, Hooks and Roact Migration|React-Lua on Roblox - Packages, Hooks and Roact Migration]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
React-Lua is a Luau translation of React (the same architecture as React JS 17-era: components, hooks, reconciler). Roblox uses it internally for its own app UI. Roblox's own repository is a read-only mirror that the community cannot contribute to and that Roblox did not publish to a package registry, so the `jsdotlua` fork exists to publish packages and accept fixes. It is meant to supplant Roact, the older...
**Useful source sections:** Packages in the repo, Minimal component with hooks, Migrating from Roact.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For React-Lua on Roblox - Packages, Hooks and Roact Migration, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using React-Lua on Roblox - Packages, Hooks and Roact Migration and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/React-Lua on Roblox - Packages, Hooks and Roact Migration|React-Lua on Roblox - Packages, Hooks and Roact Migration]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
