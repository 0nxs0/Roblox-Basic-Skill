---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Mass and Density - AssemblyMass, Massless and Custom Density.md"
---
# Physics - Mass and Density - AssemblyMass, Massless and Custom Density — Development Guide

New practical guidance for [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Mass and Density - AssemblyMass, Massless and Custom Density|Physics - Mass and Density - AssemblyMass, Massless and Custom Density]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Mass decides how hard things are to push, how far they fly from explosions, whether they float, and how much force your constraints need. In Roblox you never type a mass: you set density and the size does the rest. Knowing the few mass-related properties prevents the classic bugs: a sword that drags the player sideways, a car that flips because a decorative part weighs a ton, a crate that will not float.
**Useful source sections:** The properties (API reference), Mass from size (own code), Setting density (own code).

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Physics - Mass and Density - AssemblyMass, Massless and Custom Density, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Physics - Mass and Density - AssemblyMass, Massless and Custom Density and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Mass and Density - AssemblyMass, Massless and Custom Density|Physics - Mass and Density - AssemblyMass, Massless and Custom Density]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
