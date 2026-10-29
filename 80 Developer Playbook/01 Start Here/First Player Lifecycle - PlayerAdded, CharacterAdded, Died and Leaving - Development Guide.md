---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/Starter - First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving.md"
---
# First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/Starter - First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving|First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Half of beginner bugs are "it worked the first time, then broke after I died" or "it works in my test but not for the second player". Both come from mixing up the Player (your account in this server, created once when you join) with the Character (the body in the world, destroyed and rebuilt every time you respawn). This note maps the whole lifecycle and gives a server template that hooks each stage correctly.
**Useful source sections:** The timeline, Where to put what, A server template.

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/Starter - First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving|First Player Lifecycle - PlayerAdded, CharacterAdded, Died and Leaving]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
