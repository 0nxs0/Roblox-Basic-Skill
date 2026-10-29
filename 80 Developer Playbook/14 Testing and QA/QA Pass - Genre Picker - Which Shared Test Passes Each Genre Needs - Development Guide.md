---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs.md"
---
# QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs|QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
This vault has two kinds of QA notes: genre passes (the "QA Pass - ..." notes, one per genre) and shared passes (join/leave, dupes, purchases, streaming, saves and so on) that apply to many games. Small teams cannot run all of them every update. This page maps each genre to its own pass plus the three shared passes most likely to catch that genre's worst bugs, and gives the one test to run if you only have five...
**Useful source sections:** How to use it, Genre to pass map, Shared passes referenced above.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs|QA Pass - Genre Picker - Which Shared Test Passes Each Genre Needs]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
