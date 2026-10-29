---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Custom ProximityPrompt UI.md"
---
# Custom ProximityPrompt UI — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Custom ProximityPrompt UI|Custom ProximityPrompt UI]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The default "E - Open" prompt is fine for prototypes but clashes with every art style. ProximityPrompts already solve the hard parts: range checks, line of sight, picking the prompt the camera faces, per-device keys and hold timers. Setting `Style = Custom` keeps all of that behaviour and lets you draw your own UI. This is one of the cheapest ways to make a game look less like a template.
**Useful source sections:** What stays built in, Build it once for every prompt, BillboardGui settings for prompts.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Custom ProximityPrompt UI, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Custom ProximityPrompt UI and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Custom ProximityPrompt UI|Custom ProximityPrompt UI]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
