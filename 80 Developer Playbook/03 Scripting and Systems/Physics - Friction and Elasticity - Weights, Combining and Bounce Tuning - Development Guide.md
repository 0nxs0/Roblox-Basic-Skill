---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning.md"
---
# Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning — Development Guide

New practical guidance for [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning|Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Ice levels, bouncy castles, sticky climbing walls, sliding crates and bouncing balls are all made with two numbers per part, Friction and Elasticity, plus two often-ignored weights that decide which surface wins when two parts touch. Getting the weights right is what makes "this floor is ice for everyone" work without editing every character.
**Useful source sections:** Ranges (units page), How two parts combine (PhysicalProperties docs), Recipes (own code).

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning|Physics - Friction and Elasticity - Weights, Combining and Bounce Tuning]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
