---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/Starter - First Key Press - UserInputService, ContextActionService and Input Actions.md"
---
# First Key Press - UserInputService, ContextActionService and Input Actions — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/Starter - First Key Press - UserInputService, ContextActionService and Input Actions|First Key Press - UserInputService, ContextActionService and Input Actions]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Press F to toggle the flashlight", "press E to dash", "hold Shift to sprint": almost every game needs its own key. Roblox gives you three ways to read input, and beginners often pick the hardest one or forget that a third of players are on phones with no keyboard. This note shows the same action, toggle a flashlight on F, three ways, then how to tell the server about it.
**Useful source sections:** Way 1: UserInputService (quick and keyboard-only), Way 2: ContextActionService (adds a phone button for free), Way 3: the Input Action System (set up in Studio, newest).

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Key Press - UserInputService, ContextActionService and Input Actions, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Key Press - UserInputService, ContextActionService and Input Actions and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/Starter - First Key Press - UserInputService, ContextActionService and Input Actions|First Key Press - UserInputService, ContextActionService and Input Actions]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
