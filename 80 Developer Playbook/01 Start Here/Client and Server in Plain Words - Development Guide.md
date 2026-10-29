---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/Client and Server in Plain Words.md"
---
# Client and Server in Plain Words — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/Client and Server in Plain Words|Client and Server in Plain Words]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every Roblox game is multiplayer, even when only one person is in it. That single fact explains most "it works for me but not for my friend" bugs. Once you can say, for any line of code, "this runs on the server" or "this runs on one player's device", Roblox stops feeling random.
**Useful source sections:** The restaurant picture, The one rule that matters, Who does what.

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For Client and Server in Plain Words, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using Client and Server in Plain Words and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/Client and Server in Plain Words|Client and Server in Plain Words]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
