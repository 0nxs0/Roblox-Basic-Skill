---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Explosions - BlastPressure, Joint Radius and Custom Damage.md"
---
# Explosions - BlastPressure, Joint Radius and Custom Damage — Development Guide

New practical guidance for [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Explosions - BlastPressure, Joint Radius and Custom Damage|Explosions - BlastPressure, Joint Radius and Custom Damage]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The built-in `Explosion` instance is the quickest way to get a boom, but its defaults are brutal and unfair for most games: it breaks joints (killing any Humanoid whose neck is inside the joint radius), pushes parts with the same force no matter how close they are, and craters terrain. Almost every shipped game turns most of that off and does damage and knockback itself. This note explains each property and gives...
**Useful source sections:** Property reference (from the API docs), Pattern: custom explosion with falloff (own code), Alternative: skip the Explosion instance.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Explosions - BlastPressure, Joint Radius and Custom Damage, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Explosions - BlastPressure, Joint Radius and Custom Damage and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Explosions - BlastPressure, Joint Radius and Custom Damage|Explosions - BlastPressure, Joint Radius and Custom Damage]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
