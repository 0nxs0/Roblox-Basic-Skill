---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Group and Subscriber Perks with Chat Tags.md"
---
# Recipe - Group and Subscriber Perks with Chat Tags — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Group and Subscriber Perks with Chat Tags|Recipe - Group and Subscriber Perks with Chat Tags]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Reward players who join your Roblox community group (and, optionally, players with an active Roblox subscription) with a small perk, such as +10% coins, plus a coloured `[Group]` tag in chat. Group perks are a cheap way to grow a community you can announce updates to. Two API details matter in 2026: `Player:IsInGroup` is deprecated in favour of `Player:IsInGroupAsync`, and `Player.MembershipType` is deprecated in...
**Useful source sections:** Where it goes, Server, Client: chat tags.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Group and Subscriber Perks with Chat Tags, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Group and Subscriber Perks with Chat Tags and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Group and Subscriber Perks with Chat Tags|Recipe - Group and Subscriber Perks with Chat Tags]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
