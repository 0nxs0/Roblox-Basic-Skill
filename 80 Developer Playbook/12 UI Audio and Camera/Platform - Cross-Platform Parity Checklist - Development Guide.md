---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Cross-Platform Parity Checklist.md"
---
# Platform - Cross-Platform Parity Checklist — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Cross-Platform Parity Checklist|Platform - Cross-Platform Parity Checklist]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Parity" does not mean every device gets identical UI. It means every player can do everything in the game, at a similar effort, with the hardware in their hands. Roblox's cross-platform guide and adaptive design guidelines boil down to four principles (input fluidity, responsive layout, dynamic sizing, legibility); this checklist turns them, plus the console, VR and hardware-testing guides, into yes/no checks...
**Useful source sections:** 1. Every action, every input, 2. UI follows the player's device, 3. Screens of every size.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Cross-Platform Parity Checklist, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Cross-Platform Parity Checklist and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Cross-Platform Parity Checklist|Platform - Cross-Platform Parity Checklist]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
