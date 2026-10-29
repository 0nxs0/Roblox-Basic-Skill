---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Per-Platform Differences Developers Trip Over.md"
---
# Platform - Per-Platform Differences Developers Trip Over — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Per-Platform Differences Developers Trip Over|Platform - Per-Platform Differences Developers Trip Over]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox's promise is "build once, run everywhere", and mostly it holds. But a handful of platform-specific rules and behaviours are scattered across different doc pages, and each one has burned someone: a paid-access game that vanished from Xbox, a video trailer nobody on PlayStation saw, glyph code that returns nothing on Android. This is the cheat sheet, all checked against the Creator Docs on 2026-10-25.
**Useful source sections:** Store and discovery, Engine updates arrive at different times, Input and UI.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Per-Platform Differences Developers Trip Over, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Per-Platform Differences Developers Trip Over and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Per-Platform Differences Developers Trip Over|Platform - Per-Platform Differences Developers Trip Over]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
