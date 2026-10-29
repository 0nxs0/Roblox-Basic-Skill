---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Custom Buoyancy Math - Archimedes with VectorForce.md"
---
# Physics - Custom Buoyancy Math - Archimedes with VectorForce — Development Guide

New practical guidance for [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Custom Buoyancy Math - Archimedes with VectorForce|Physics - Custom Buoyancy Math - Archimedes with VectorForce]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Terrain water already floats parts lighter than water, but many games use part water (a blue box, a moving wave mesh, a flood that rises) where the engine does nothing. Then you write buoyancy yourself. The math is Archimedes plus a damping term, and in Roblox units it is unusually clean because water density is exactly 1 RMU/stud3.
**Useful source sections:** The principle, Per-point buoyancy for boats (own code), Why damping matters.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Physics - Custom Buoyancy Math - Archimedes with VectorForce, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Physics - Custom Buoyancy Math - Archimedes with VectorForce and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Custom Buoyancy Math - Archimedes with VectorForce|Physics - Custom Buoyancy Math - Archimedes with VectorForce]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
