---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack.md"
---
# Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack|Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Many Roblox developers debug only with `print`. The built-in debugger is faster for anything involving state: it pauses the game at a line, shows every local and upvalue, and lets you step through calls. Logpoints give you prints without editing code, which matters because a forgotten `print` in a hot loop is itself a performance bug. Here is how to use it well.
**Useful source sections:** Four breakpoint types, Edit options worth knowing, The workflow.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack|Studio Debugger - Breakpoints, Logpoints, Watch and Call Stack]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
