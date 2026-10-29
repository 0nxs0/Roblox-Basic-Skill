---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices.md"
---
# Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices|Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every cross-platform HUD has one switch at its heart: "which controls is this player using right now?". Get it wrong and a tablet player with a Bluetooth controller sees touch buttons covering the screen, or a touchscreen laptop user gets phone controls. Roblox now has one property built for this question, `UserInputService.PreferredInput`, plus several older ones that answer narrower questions. This note says...
**Useful source sections:** The APIs and what each one really answers, One input-mode module, read everywhere, Hybrid devices to keep in mind.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices|Platform - Input Mode Detection - PreferredInput, TouchEnabled and Hybrid Devices]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
