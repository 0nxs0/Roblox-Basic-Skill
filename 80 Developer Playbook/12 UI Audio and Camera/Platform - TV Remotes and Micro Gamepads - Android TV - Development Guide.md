---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - TV Remotes and Micro Gamepads - Android TV.md"
---
# Platform - TV Remotes and Micro Gamepads - Android TV — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - TV Remotes and Micro Gamepads - Android TV|Platform - TV Remotes and Micro Gamepads - Android TV]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Some Roblox players sit in front of a smart TV holding a remote with arrows, a centre button and a back button, and nothing else. Roblox calls these micro gamepads. Most games are unplayable with one because they assume two sticks. You probably will not design a whole game around a remote, but your menus, lobby and shop should work with one, and simple genres (quiz, idle, tycoon management) can be fully...
**Useful source sections:** What a remote sends today, Detecting a remote, Making the game remote-friendly.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - TV Remotes and Micro Gamepads - Android TV, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - TV Remotes and Micro Gamepads - Android TV and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - TV Remotes and Micro Gamepads - Android TV|Platform - TV Remotes and Micro Gamepads - Android TV]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
