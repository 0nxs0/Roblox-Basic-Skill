---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - AFK Detection.md"
---
# Recipe - AFK Detection — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - AFK Detection|Recipe - AFK Detection]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Mark players as AFK after a period without input: show an "AFK" tag over their head, skip them when starting rounds or balancing teams, and pause idle-farm rewards if you want to. The engine already has `Player.Idled`, but per the docs it only fires on the client, starts about two minutes after the engine considers the player idle, and Roblox disconnects players idle for at least 20 minutes. Most games want a...
**Useful source sections:** Where it goes, Client: detect inactivity, Server: own the flag and the tag.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - AFK Detection, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - AFK Detection and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - AFK Detection|Recipe - AFK Detection]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
