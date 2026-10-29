---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint.md"
---
# First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint|First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Changing how the player moves is the quickest way to make a Roblox game feel like yours: faster runs for an obby, floaty jumps for a moon level, more health for a boss game, a sprint key for a horror game. All of it lives on the Humanoid inside each character, with game-wide defaults on StarterPlayer. This note covers the safe places to change each value and the respawn trap that catches every beginner.
**Useful source sections:** Game-wide defaults (no code): StarterPlayer, Per-player changes: server Script, Sprint key: LocalScript in StarterCharacterScripts.

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint|First Character Tweaks - WalkSpeed, JumpHeight, Health and Sprint]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
