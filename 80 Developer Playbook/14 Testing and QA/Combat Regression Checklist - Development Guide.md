---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Test - Combat Regression Checklist.md"
---
# Combat Regression Checklist — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Test - Combat Regression Checklist|Combat Regression Checklist]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Combat code is touched constantly (new weapons, balance passes, animation swaps) and breaks in ways that players notice within minutes: hits that do not register, double damage, or a stun that never ends. A fixed regression checklist, run after every combat change, catches the repeat offenders without re-thinking the test each time. Run it in Studio's multi-client Server and Clients mode with 2 clients plus 1 NPC...
**Useful source sections:** A. Hit registration, B. Damage and health, C. Timing and state.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Combat Regression Checklist, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Combat Regression Checklist and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Test - Combat Regression Checklist|Combat Regression Checklist]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
