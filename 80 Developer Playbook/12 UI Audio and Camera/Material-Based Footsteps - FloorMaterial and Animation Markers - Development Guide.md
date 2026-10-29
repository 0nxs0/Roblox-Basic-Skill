---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Audio/Community Knowledge/Material-Based Footsteps - FloorMaterial and Animation Markers.md"
---
# Material-Based Footsteps - FloorMaterial and Animation Markers — Development Guide

New practical guidance for [[12 UI Audio and Camera/Audio/Community Knowledge/Material-Based Footsteps - FloorMaterial and Animation Markers|Material-Based Footsteps - FloorMaterial and Animation Markers]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Footsteps that match the surface (wood creak, metal clang, grass rustle, splash in water) make a world feel solid, and in horror and stealth games they are gameplay: you hear where the threat is. The default character sound is one looping run sound for everything. A good custom system has three parts: when a foot lands, what it lands on, and how it sounds without repeating.
**Useful source sections:** 1. When: animation markers, with a fallback, 2. What: the surface, 3. How: variation without repetition.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Material-Based Footsteps - FloorMaterial and Animation Markers, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Material-Based Footsteps - FloorMaterial and Animation Markers and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Audio/Community Knowledge/Material-Based Footsteps - FloorMaterial and Animation Markers|Material-Based Footsteps - FloorMaterial and Animation Markers]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
