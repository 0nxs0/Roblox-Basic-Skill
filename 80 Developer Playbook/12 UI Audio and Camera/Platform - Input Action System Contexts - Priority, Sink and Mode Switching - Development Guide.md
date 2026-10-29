---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Input Action System Contexts - Priority, Sink and Mode Switching.md"
---
# Platform - Input Action System Contexts - Priority, Sink and Mode Switching — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Input Action System Contexts - Priority, Sink and Mode Switching|Platform - Input Action System Contexts - Priority, Sink and Mode Switching]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The Input Action System (IAS) lets one action ("Attack") be driven by a key, a trigger and a touch button. The part that makes or breaks a real game is contexts: which set of actions is live while the player is on foot, driving, in a shop or typing. Done right, a gamepad's A button jumps on foot, confirms in menus and does nothing while chatting, with no `if menuOpen then` checks scattered through your code. This...
**Useful source sections:** The three properties that matter, A layout that scales, The held-input trap.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Input Action System Contexts - Priority, Sink and Mode Switching, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Input Action System Contexts - Priority, Sink and Mode Switching and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Input Action System Contexts - Priority, Sink and Mode Switching|Platform - Input Action System Contexts - Priority, Sink and Mode Switching]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
