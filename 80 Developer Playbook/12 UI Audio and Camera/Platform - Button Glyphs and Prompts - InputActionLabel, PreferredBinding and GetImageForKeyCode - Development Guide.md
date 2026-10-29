---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode.md"
---
# Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode|Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"Press E to open" on an Xbox is the fastest way to tell a console player your game was not made for them. Prompts must show the right glyph for the device in hand: a key on keyboard, a Cross/Circle on PlayStation, A/B on Xbox, nothing (or a tap icon) on touch. Roblox gives three tiers of help, from zero-code to fully custom.
**Useful source sections:** Tier 1: InputActionLabel (no code), Tier 2: PreferredBinding (custom layout), Tier 3: the raw helpers.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode|Platform - Button Glyphs and Prompts - InputActionLabel, PreferredBinding and GetImageForKeyCode]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
