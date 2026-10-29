---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Wall Jump.md"
---
# Recipe - Wall Jump — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Wall Jump|Recipe - Wall Jump]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
While falling next to a wall, press jump to kick off it: up and away from the wall, facing out. Players can then climb a shaft by bouncing between two walls. DevForum threads on wall jumps mostly agree on the approach used here: a short raycast from the HumanoidRootPart to find the wall, the hit normal to decide the push direction, and a brief velocity burst because the Humanoid's air control would otherwise...
**Useful source sections:** Where it goes, The code, Living with Recipe - Double Jump.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Wall Jump, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Wall Jump and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Wall Jump|Recipe - Wall Jump]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
