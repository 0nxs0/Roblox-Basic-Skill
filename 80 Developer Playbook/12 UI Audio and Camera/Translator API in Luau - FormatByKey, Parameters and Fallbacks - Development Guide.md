---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Accessibility Localization/Community Knowledge/Translator API in Luau - FormatByKey, Parameters and Fallbacks.md"
---
# Translator API in Luau - FormatByKey, Parameters and Fallbacks — Development Guide

New practical guidance for [[12 UI Audio and Camera/Accessibility Localization/Community Knowledge/Translator API in Luau - FormatByKey, Parameters and Fallbacks|Translator API in Luau - FormatByKey, Parameters and Fallbacks]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox's automatic translation catches static UI text, but scripted text ("You earned 1,250 coins", "Wave 7 begins in 5", item names built from data) slips through or gets translated badly because the number is baked into the string. The fix is to keep text in a localization table with keys and parameters, and format it at runtime with a `Translator`. Most of the world's Roblox players don't play in English, so...
**Useful source sections:** The objects, Table entries with parameters, A small helper module.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Translator API in Luau - FormatByKey, Parameters and Fallbacks, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Translator API in Luau - FormatByKey, Parameters and Fallbacks and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Accessibility Localization/Community Knowledge/Translator API in Luau - FormatByKey, Parameters and Fallbacks|Translator API in Luau - FormatByKey, Parameters and Fallbacks]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
