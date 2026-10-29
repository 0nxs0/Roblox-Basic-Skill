---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Hidden Collectibles Hunt Saved per Player.md"
---
# Recipe - Hidden Collectibles Hunt Saved per Player — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Hidden Collectibles Hunt Saved per Player|Recipe - Hidden Collectibles Hunt Saved per Player]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Find all 25 hidden eggs": each collectible can be picked up once per player, forever, other players still see their own copy, and progress ("12/25") is saved. The official coin tutorial covers shared coins that come back after a cooldown; a per-player hunt needs a different shape: the server records which IDs this player has, and each client hides the ones it already collected, locally.
**Useful source sections:** Where it goes, Server, Client.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Hidden Collectibles Hunt Saved per Player, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Hidden Collectibles Hunt Saved per Player and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Hidden Collectibles Hunt Saved per Player|Recipe - Hidden Collectibles Hunt Saved per Player]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
