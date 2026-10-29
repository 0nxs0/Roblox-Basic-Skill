---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/First Tool - A Sword or Flashlight You Can Equip.md"
---
# First Tool - A Sword or Flashlight You Can Equip — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/First Tool - A Sword or Flashlight You Can Equip|First Tool - A Sword or Flashlight You Can Equip]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A Tool is anything a player holds from the hotbar: swords, flashlights, keys, wands, guns. Roblox handles the backpack, hotbar slots, equipping and the holding animation for you; you supply a model with a `Handle` and scripts that react to `Activated`. This note builds a flashlight (client-safe) and a simple sword (server damage), the two shapes nearly every tool follows.
**Useful source sections:** Anatomy of a tool, Where to put it, Flashlight (toggle on click).

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First Tool - A Sword or Flashlight You Can Equip, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First Tool - A Sword or Flashlight You Can Equip and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/First Tool - A Sword or Flashlight You Can Equip|First Tool - A Sword or Flashlight You Can Equip]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
