---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Physics Ragdolls/Community Knowledge/R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery.md"
---
# R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery — Development Guide

New practical guidance for [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery|R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Ragdolls sell impact: knockouts, explosions, deaths, being hit by a car. The standard Roblox technique is to swap each `Motor6D` joint for a `BallSocketConstraint` at the same attachment points, then swap back to recover. DevForum help threads show the same failures again and again (instant death, floating, limbs bending backwards, jitter, dangling from the root). This note is the setup that avoids them. For the...
**Useful source sections:** The core idea, Humanoid settings that prevent the classic bugs, Joint limits (stop limbs bending backwards).

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Physics Ragdolls/Community Knowledge/R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery|R15 Ragdoll with BallSocketConstraints - Setup, Limits and Recovery]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
