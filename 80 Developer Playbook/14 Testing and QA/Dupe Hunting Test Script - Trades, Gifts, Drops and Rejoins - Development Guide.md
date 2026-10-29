---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Test - Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins.md"
---
# Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Test - Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins|Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
An item duplication bug can wreck an economy in a weekend: once a dupe method spreads, rare items lose their value and players who traded fairly feel cheated. Dupes almost never need an exploit executor; they come from timing (leave at the right moment), from two servers holding the same player's data, or from a remote that can be fired twice before the first call finishes. The design defences are in Trading and...
**Useful source sections:** Setup, Case list, What the defences should look like when they pass.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Test - Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins|Dupe Hunting Test Script - Trades, Gifts, Drops and Rejoins]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
