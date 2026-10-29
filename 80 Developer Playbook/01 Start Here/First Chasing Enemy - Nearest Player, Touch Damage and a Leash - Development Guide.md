---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/Starter - First Chasing Enemy - Nearest Player, Touch Damage and a Leash.md"
---
# First Chasing Enemy - Nearest Player, Touch Damage and a Leash — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/Starter - First Chasing Enemy - Nearest Player, Touch Damage and a Leash|First Chasing Enemy - Nearest Player, Touch Damage and a Leash]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The first enemy most beginners want is a zombie or slime that runs at the nearest player and hurts them on contact. It is a great learning project because it combines a loop, distance math, Humanoids, debounce and respawning. This version is deliberately simple: no pathfinding, one server Script, and three rules (find, chase, give up). It builds on Starter - First Patrol NPC - Waypoints with MoveTo and...
**Useful source sections:** Setup, The brain: one server Script in ServerScriptService, What each part teaches.

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Chasing Enemy - Nearest Player, Touch Damage and a Leash, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Chasing Enemy - Nearest Player, Touch Damage and a Leash and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/Starter - First Chasing Enemy - Nearest Player, Touch Damage and a Leash|First Chasing Enemy - Nearest Player, Touch Damage and a Leash]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
