---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/First GUI Button - ScreenGui, TextButton and Activated.md"
---
# First GUI Button - ScreenGui, TextButton and Activated — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/First GUI Button - ScreenGui, TextButton and Activated|First GUI Button - ScreenGui, TextButton and Activated]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Almost every game needs on-screen buttons: Shop, Settings, Play, Sprint. A first button teaches the whole UI pipeline: where UI lives (StarterGui copies into each player's PlayerGui), why UI code is a LocalScript, how to size things so they work on phones, and how a button asks the server to do something. This note builds a toggle menu with an Open button that works on PC, phone and console.
**Useful source sections:** 1. The objects, 2. Size it for every screen, 3. The script (LocalScript in OpenButton).

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First GUI Button - ScreenGui, TextButton and Activated, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First GUI Button - ScreenGui, TextButton and Activated and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/First GUI Button - ScreenGui, TextButton and Activated|First GUI Button - ScreenGui, TextButton and Activated]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
