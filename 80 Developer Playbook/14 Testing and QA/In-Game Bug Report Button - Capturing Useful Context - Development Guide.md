---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/In-Game Bug Report Button - Capturing Useful Context.md"
---
# In-Game Bug Report Button - Capturing Useful Context — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/In-Game Bug Report Button - Capturing Useful Context|In-Game Bug Report Button - Capturing Useful Context]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Players report bugs in Discord as "game broken pls fix". An in-game report button that silently attaches the build, server, device and the last log lines turns those into actionable tickets, and players use it far more than an external form because it is right there. This note covers what to collect, how to send it safely and where to store it.
**Useful source sections:** What to attach automatically, Client side, Server side: validate, limit, store.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For In-Game Bug Report Button - Capturing Useful Context, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using In-Game Bug Report Button - Capturing Useful Context and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/In-Game Bug Report Button - Capturing Useful Context|In-Game Bug Report Button - Capturing Useful Context]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
