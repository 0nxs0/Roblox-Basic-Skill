---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Console Release Checklist - Xbox and PlayStation.md"
---
# Platform - Console Release Checklist - Xbox and PlayStation — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Console Release Checklist - Xbox and PlayStation|Platform - Console Release Checklist - Xbox and PlayStation]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
This is not an official certification list. Roblox publishes console development guidelines, and a few platform rules in other docs act as hard gates. A game that ignores them may be hard to use on a TV, may be filtered out for missing maturity information, or may simply not be offered on a console. This is the list to walk through before you tick the console box. The "why" behind 10-foot UI is in Gamepad and...
**Useful source sections:** A. Settings and policy (hard requirements), B. Input, C. Screen.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Console Release Checklist - Xbox and PlayStation, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Console Release Checklist - Xbox and PlayStation and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Console Release Checklist - Xbox and PlayStation|Platform - Console Release Checklist - Xbox and PlayStation]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
