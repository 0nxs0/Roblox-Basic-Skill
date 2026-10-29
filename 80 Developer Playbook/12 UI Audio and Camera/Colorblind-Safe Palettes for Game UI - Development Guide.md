---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Accessibility Localization/Community Knowledge/Colorblind-Safe Palettes for Game UI.md"
---
# Colorblind-Safe Palettes for Game UI — Development Guide

New practical guidance for [[12 UI Audio and Camera/Accessibility Localization/Community Knowledge/Colorblind-Safe Palettes for Game UI|Colorblind-Safe Palettes for Game UI]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox's own accessibility guidelines say over 5% of people have some form of colour blindness, and the Game Accessibility Guidelines put red/green difficulty at roughly 8-10% of males. In a 30-player server that is often two or three players who can't tell your red team from your green team, your "rare" from your "common", or a poison puddle from a heal zone. The fix is cheap if you plan it early: a palette...
**Useful source sections:** Rule 1: colour is never the only signal, Rule 2: pick hues that survive, Rule 3: contrast and value.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Colorblind-Safe Palettes for Game UI, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Colorblind-Safe Palettes for Game UI and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Accessibility Localization/Community Knowledge/Colorblind-Safe Palettes for Game UI|Colorblind-Safe Palettes for Game UI]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
