---
kind: development-companion
category: "05 Performance and Optimization"
source-note: "05 Performance and Optimization/Optimization/Community Knowledge/Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers.md"
---
# Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers — Development Guide

New practical guidance for [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers|Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Strings in Luau are immutable and interned: every `a .. b` makes a brand-new string and copies both sides into it. That is fine for a label, but building a big string piece by piece in a loop (a save-file export, a debug dump, a chat log, a serialized map) copies the growing result again on every step. The cost grows with the square of the final length and produces a burst of garbage. This note shows the three...
**Useful source sections:** Why the loop is quadratic, Method 1: `..` and interpolation (small, fixed strings), Method 2: `table.concat` (variable-length text).

## Apply it
Use this topic as part of **measure before tuning**.
- **Define the contract:** For Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.

## Validate before shipping
- **Expected path:** Build one small feature using Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Record before/after measurements and test a low-end device under load.

## Connected work
- Source note: [[05 Performance and Optimization/Optimization/Community Knowledge/Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers|Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers]]
- Category hub: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
