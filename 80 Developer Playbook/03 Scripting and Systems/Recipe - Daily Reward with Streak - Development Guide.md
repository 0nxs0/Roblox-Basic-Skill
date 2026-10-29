---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Daily Reward with Streak.md"
---
# Recipe - Daily Reward with Streak — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Daily Reward with Streak|Recipe - Daily Reward with Streak]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A "Claim daily reward" button that pays once per UTC day, grows over a 7-day streak, and resets the streak if a day is missed. Daily rewards are a standard retention hook (design advice in Streaks With Grace - Freezes, Repairs and Loss Aversion); the code side has to get three things right: the server's clock decides the day, the claim is written with `UpdateAsync` so two servers cannot both pay, and the reward...
**Useful source sections:** Where it goes, Server, Client.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Daily Reward with Streak, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Daily Reward with Streak and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Daily Reward with Streak|Recipe - Daily Reward with Streak]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
