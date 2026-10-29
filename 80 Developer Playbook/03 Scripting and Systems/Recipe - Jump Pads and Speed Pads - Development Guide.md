---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Jump Pads and Speed Pads.md"
---
# Recipe - Jump Pads and Speed Pads — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Jump Pads and Speed Pads|Recipe - Jump Pads and Speed Pads]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Step on a glowing pad and get launched upward (jump pad) or get a few seconds of extra speed (speed pad). Obbies, lobbies and racing maps use dozens of them. The non-obvious part: the server should not push player characters. Each client owns its own character's physics, so a velocity set by the server on a player's root is overwritten by the client a moment later and feels laggy or does nothing. Let each client...
**Useful source sections:** Where it goes, The code, How to test.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Jump Pads and Speed Pads, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Jump Pads and Speed Pads and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Jump Pads and Speed Pads|Recipe - Jump Pads and Speed Pads]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
