---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/Starter - First Patrol NPC - Waypoints with MoveTo and MoveToFinished.md"
---
# First Patrol NPC - Waypoints with MoveTo and MoveToFinished — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/Starter - First Patrol NPC - Waypoints with MoveTo and MoveToFinished|First Patrol NPC - Waypoints with MoveTo and MoveToFinished]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A guard walking a loop, a shopkeeper pacing behind the counter, a villager strolling the square: a patrolling NPC is the first thing that makes a map feel alive, and it needs only one method, `Humanoid:MoveTo()`. This note builds a guard that walks a list of waypoint parts forever, and covers the two things that trip beginners: the 8-second timeout and stutter when players get close.
**Useful source sections:** 1. Make the NPC, 2. Lay out waypoints, 3. The script.

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Patrol NPC - Waypoints with MoveTo and MoveToFinished, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Patrol NPC - Waypoints with MoveTo and MoveToFinished and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/Starter - First Patrol NPC - Waypoints with MoveTo and MoveToFinished|First Patrol NPC - Waypoints with MoveTo and MoveToFinished]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
