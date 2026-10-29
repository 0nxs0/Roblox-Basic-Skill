---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA Debug Overlay - Build, FPS, Ping and Game State On Screen.md"
---
# QA Debug Overlay - Build, FPS, Ping and Game State On Screen — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA Debug Overlay - Build, FPS, Ping and Game State On Screen|QA Debug Overlay - Build, FPS, Ping and Game State On Screen]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
When a tester sends a screenshot or clip of a bug, the most useful thing in it is information you cannot see in the game: which build, which server, what the frame time and ping were, what state the round was in. A small debug overlay that testers can toggle puts that in every capture for free. It also speeds up your own playtests, because you stop opening the Developer Console to check basic numbers.
**Useful source sections:** What to show, Client script, Who can see it.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA Debug Overlay - Build, FPS, Ping and Game State On Screen, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA Debug Overlay - Build, FPS, Ping and Game State On Screen and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA Debug Overlay - Build, FPS, Ping and Game State On Screen|QA Debug Overlay - Build, FPS, Ping and Game State On Screen]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
