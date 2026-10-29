---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats.md"
---
# Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats|Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Developers often want to "detect a low-end device and turn things off". Roblox deliberately gives you only part of that picture: you can read what the player chose, and you can measure how the frame is actually performing, but you cannot read the engine's live automatic quality level. Knowing exactly what is and is not readable saves you from building on properties that always error. This note is the reference;...
**Useful source sections:** What you can read about graphics quality, What the quality level changes (and why you should not depend on it), What you can measure: Stats (client only).

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats|Platform - Reading Graphics Quality and Frame Time - UserGameSettings and Stats]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
