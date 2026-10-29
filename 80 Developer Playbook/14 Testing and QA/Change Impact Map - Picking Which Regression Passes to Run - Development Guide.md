---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Test - Change Impact Map - Picking Which Regression Passes to Run.md"
---
# Change Impact Map - Picking Which Regression Passes to Run — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Test - Change Impact Map - Picking Which Regression Passes to Run|Change Impact Map - Picking Which Regression Passes to Run]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
This vault now has many test passes (combat, economy, UI state, teleport, streaming, dupes, chaos, purchases, safety). Nobody runs all of them every Friday, and a small team should not try. A change impact map answers "which passes does this release need?" in two minutes: list what changed, look up each change type in a table, and run the union. It is risk-based testing in its simplest form: spend test time where...
**Useful source sections:** Step 1 - List what changed, Step 2 - Look up each change, Step 3 - Always run the smoke set.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Change Impact Map - Picking Which Regression Passes to Run, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Change Impact Map - Picking Which Regression Passes to Run and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Test - Change Impact Map - Picking Which Regression Passes to Run|Change Impact Map - Picking Which Regression Passes to Run]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
