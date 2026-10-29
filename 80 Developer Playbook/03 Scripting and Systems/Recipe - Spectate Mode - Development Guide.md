---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Spectate Mode.md"
---
# Recipe - Spectate Mode — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Spectate Mode|Recipe - Spectate Mode]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Eliminated players (or players waiting in the lobby) can watch the players still in the round, flipping between them with Prev/Next buttons or Q/E. It keeps dead players engaged instead of leaving. The camera part is one line (`Camera.CameraSubject = targetHumanoid`); the parts people forget are skipping players who die or leave, and StreamingEnabled: the spectator's client may not have the far-away target...
**Useful source sections:** Where it goes, Server: replication focus, Client.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Spectate Mode, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Spectate Mode and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Spectate Mode|Recipe - Spectate Mode]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
