---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Pre-Release Gate.md"
---
# Pre-Release Gate — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Pre-Release Gate|Pre-Release Gate]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Do not publish a major release until all CRITICAL items pass.
**Useful source sections:** Knowledge Graph Connections.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Pre-Release Gate, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Pre-Release Gate and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Pre-Release Gate|Pre-Release Gate]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
