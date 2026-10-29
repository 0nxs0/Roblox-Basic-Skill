---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Roblox Device Share Stats and What They Mean for Design (dated).md"
---
# Platform - Roblox Device Share Stats and What They Mean for Design (dated) — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Roblox Device Share Stats and What They Mean for Design (dated)|Platform - Roblox Device Share Stats and What They Mean for Design (dated)]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Design for mobile first" is repeated so often that it is worth seeing the actual numbers, with dates and how solid each one is. Platform shares shift every year (consoles and new regions grow), so every figure below carries its period and source. Re-check them yearly; your own game's split, from the Performance Dashboard, beats any platform average.
**Useful source sections:** The numbers, Reading the numbers correctly, Your own numbers.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Roblox Device Share Stats and What They Mean for Design (dated), write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Roblox Device Share Stats and What They Mean for Design (dated) and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Roblox Device Share Stats and What They Mean for Design (dated)|Platform - Roblox Device Share Stats and What They Mean for Design (dated)]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
