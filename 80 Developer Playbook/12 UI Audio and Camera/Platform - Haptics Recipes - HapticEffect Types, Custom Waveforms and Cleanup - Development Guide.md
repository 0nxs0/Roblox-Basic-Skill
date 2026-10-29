---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup.md"
---
# Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup|Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Vibration is the cheapest "juice" on phones and pads: a 40 ms tick on a button press makes UI feel solid, and a heavy rumble sells an explosion better than any particle. Roblox's `HapticEffect` instance works across phones, PlayStation and Xbox pads and Quest Touch controllers with one API. This note gives ready recipes and the cleanup rules. For driving/engine rumble specifically, see Vehicle Haptics - Rumble...
**Useful source sections:** Where it works, The preset types (`Enum.HapticEffectType`), Properties and methods.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup|Platform - Haptics Recipes - HapticEffect Types, Custom Waveforms and Cleanup]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
