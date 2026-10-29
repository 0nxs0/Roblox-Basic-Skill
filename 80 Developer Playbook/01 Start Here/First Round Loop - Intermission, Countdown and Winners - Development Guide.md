---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/First Round Loop - Intermission, Countdown and Winners.md"
---
# First Round Loop - Intermission, Countdown and Winners — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/First Round Loop - Intermission, Countdown and Winners|First Round Loop - Intermission, Countdown and Winners]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Round-based games (survive the disaster, tag, sword fights, minigames) all share one heartbeat: wait for players, count down, teleport everyone in, play until a timer ends or someone wins, announce, repeat. Writing this loop yourself is an excellent step after an obby, because it combines server state, timers, teleporting and UI. This note builds a minimal but correct loop in one server script plus one LocalScript.
**Useful source sections:** What the server owns, Setup, Server Script (ServerScriptService).

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Round Loop - Intermission, Countdown and Winners, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Round Loop - Intermission, Countdown and Winners and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/First Round Loop - Intermission, Countdown and Winners|First Round Loop - Intermission, Countdown and Winners]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
