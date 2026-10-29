---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/First Leaderboard with leaderstats.md"
---
# First Leaderboard with leaderstats — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/First Leaderboard with leaderstats|First Leaderboard with leaderstats]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The player list in the top-right corner doubles as a free leaderboard. Put a Folder called `leaderstats` inside a player and every value object in it shows as a column. It is the fastest way to show coins, kills or stage, and it is the first "server owns the numbers" system most developers build. In 2026 the same list also has Friends and Global views backed by an ordered data store (beta).
**Useful source sections:** The three views, Build it (server Script in ServerScriptService), Change a stat (server only).

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Leaderboard with leaderstats, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Leaderboard with leaderstats and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/First Leaderboard with leaderstats|First Leaderboard with leaderstats]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
