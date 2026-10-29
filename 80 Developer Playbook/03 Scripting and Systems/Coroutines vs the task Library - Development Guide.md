---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Deep Dives/Coroutines vs the task Library.md"
---
# Coroutines vs the task Library — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Deep Dives/Coroutines vs the task Library|Coroutines vs the task Library]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
1. A thread (Luau `coroutine`) is a paused-able function call with its own stack. Every Script starts as one thread; every connected event handler runs in a thread. 2. Only one thread runs at a time per Luau VM (Parallel Luau aside); a thread runs until it yields or finishes. 3. The engine's task scheduler resumes yielded threads at fixed resumption points in the frame (input, `PreRender`, `PreAnimation`,...
**Useful source sections:** 1. The mental model in five sentences, 2. The task library, precisely, 3. The coroutine library, and when you still need it.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Coroutines vs the task Library, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Coroutines vs the task Library and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Deep Dives/Coroutines vs the task Library|Coroutines vs the task Library]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
