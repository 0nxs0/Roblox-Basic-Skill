---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Team Test - Collaborative Playtesting in Studio.md"
---
# Team Test - Collaborative Playtesting in Studio — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Team Test - Collaborative Playtesting in Studio|Team Test - Collaborative Playtesting in Studio]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Local "Server & Clients" tests run every player on your own machine. Team Test is different: it runs a real server session that other collaborators join from their own Studio, on their own hardware and network. It is the quickest way to test social features, real latency between people and "does this work for someone who is not me" without publishing a build to a test place.
**Useful source sections:** How it works (from the testing-modes docs), When to use which mode, A 20-minute Team Test script.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Team Test - Collaborative Playtesting in Studio, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Team Test - Collaborative Playtesting in Studio and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Team Test - Collaborative Playtesting in Studio|Team Test - Collaborative Playtesting in Studio]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
