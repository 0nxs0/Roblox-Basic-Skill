---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity.md"
---
# Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity — Development Guide

New practical guidance for [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity|Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every force, stiffness and density field in Roblox is in Roblox units, and copying real-world numbers ("a car spring is 30,000 N/m") straight in gives nonsense. This sheet collects the official conversions from the Roblox units page and turns them into the rules of thumb you need when tuning constraints, VectorForces and custom materials.
**Useful source sections:** Primary units (official), Derived units (official, rounded to 3 significant figures), Gravity.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity|Physics - Roblox Units Cheat Sheet - Studs, RMU, Rowtons and Gravity]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
