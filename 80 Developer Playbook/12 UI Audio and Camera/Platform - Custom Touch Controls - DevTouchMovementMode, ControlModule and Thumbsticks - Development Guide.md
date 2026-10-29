---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks.md"
---
# Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks|Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The default Roblox touch controls (a stick bottom-left, jump bottom-right) are good enough for most games, and players already know them. You change them when the genre needs it: a 2D side-scroller, a top-down shooter with twin sticks, a car game with pedals, or a cutscene where nothing should be on screen. This note covers the four levels of control, from a property flip to a fully custom stick.
**Useful source sections:** Level 1: pick a built-in scheme, Level 2: hide the default UI for a moment, Level 3: read or drive the default controls.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks|Platform - Custom Touch Controls - DevTouchMovementMode, ControlModule and Thumbsticks]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
