---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Test - UI State Regression Checklist - Menus, Modals, Respawn and Live Data.md"
---
# UI State Regression Checklist - Menus, Modals, Respawn and Live Data — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Test - UI State Regression Checklist - Menus, Modals, Respawn and Live Data|UI State Regression Checklist - Menus, Modals, Respawn and Live Data]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Cross-device layout is covered by Platform - Cross-Platform Parity Checklist. This checklist covers the other half of UI bugs: state. Menus that open on top of each other, a shop that keeps showing yesterday's coins, a modal that leaves the character frozen, or a menu that resets every time you die. These come back every time someone refactors a menu, adds a new window or changes how data reaches the client, so...
**Useful source sections:** A. Open / close, B. Respawn and teleport, C. Live data binding.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For UI State Regression Checklist - Menus, Modals, Respawn and Live Data, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using UI State Regression Checklist - Menus, Modals, Respawn and Live Data and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Test - UI State Regression Checklist - Menus, Modals, Respawn and Live Data|UI State Regression Checklist - Menus, Modals, Respawn and Live Data]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
