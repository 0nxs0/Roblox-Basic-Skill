---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Math Geometry/Community Knowledge/Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags.md"
---
# Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags — Development Guide

New practical guidance for [[03 Scripting and Systems/Math Geometry/Community Knowledge/Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags|Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Pure random picks feel unfair: the same map three rounds in a row, the same quest twice, the killer chosen four times. Players read streaks as bugs. Two tools fix this: a correct shuffle (every order equally likely) and a shuffle bag (draw without replacement, refill when empty). Roblox's `Random` object already ships a correct shuffle.
**Useful source sections:** Random:Shuffle, Writing Fisher-Yates yourself (own code), Shuffle bag: no repeats until all are used (own code).

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Math Geometry/Community Knowledge/Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags|Math - Shuffles and No-Repeat Draws - Fisher-Yates and Shuffle Bags]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
