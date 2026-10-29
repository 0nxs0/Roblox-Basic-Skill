---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Touch Target Sizes and Mobile-First HUD Layout.md"
---
# Platform - Touch Target Sizes and Mobile-First HUD Layout — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Touch Target Sizes and Mobile-First HUD Layout|Platform - Touch Target Sizes and Mobile-First HUD Layout]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox's own design guide says the majority of users play on mobile, so UI should be designed around mobile first and then extended with gamepad and keyboard shortcuts. "Mobile first" is concrete: decide what fits on a phone, make it big enough for a thumb, and only then add the extras desktop can afford. The vault's safe-area note covers notches and reserved corners; this note covers sizes and the HUD plan.
**Useful source sections:** How big is "big enough"?, Spacing, The mobile-first HUD plan.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Touch Target Sizes and Mobile-First HUD Layout, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Touch Target Sizes and Mobile-First HUD Layout and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Touch Target Sizes and Mobile-First HUD Layout|Platform - Touch Target Sizes and Mobile-First HUD Layout]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
