---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild.md"
---
# The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild|The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every script has to find things: a part, a player's stats, a RemoteEvent, a GUI. In Roblox everything is an Instance in one big tree called the data model, rooted at `game`. Most beginner errors ("is not a valid member of", "attempt to index nil", "infinite yield") are really "I looked for an object in the wrong place, or before it existed". This note gives you the four ways to find things and when to use each.
**Useful source sections:** The tree, Way 1: GetService for top-level services, Way 2: dot indexing (when you know it exists).

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild|The Data Model and Finding Objects - GetService, FindFirstChild, WaitForChild]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
