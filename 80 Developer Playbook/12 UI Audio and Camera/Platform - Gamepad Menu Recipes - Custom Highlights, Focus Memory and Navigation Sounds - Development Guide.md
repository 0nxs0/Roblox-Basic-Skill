---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds.md"
---
# Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds|Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The vault's safe-area note already covers the basics of gamepad selection (`Selectable`, `SelectedObject`, `SelectionGroup`, `NextSelection`). This note is the polish layer that console players notice: a selection highlight that matches your art style, menus that remember where you were, a back button that always works, and soft sound/haptic ticks as focus moves. The console guidelines explicitly recommend audio...
**Useful source sections:** 1. Replace the default selection box, 2. Focus memory per menu, 3. A back button that always works.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds|Platform - Gamepad Menu Recipes - Custom Highlights, Focus Memory and Navigation Sounds]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
