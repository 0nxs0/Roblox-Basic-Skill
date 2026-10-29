---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR.md"
---
# Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR|Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Typing is easy on a PC and painful everywhere else. On a phone the on-screen keyboard covers half the screen, often right over your text box. On a console or VR headset, typing means a slow virtual keyboard driven by a stick or laser. Any flow that requires typing (naming a pet, searching a catalog, entering a code) is a drop-off point on most devices. This note covers the APIs that help and the design rules that...
**Useful source sections:** APIs for on-screen keyboards, Recipe: keep the text box above the keyboard, Recipe: submit on mobile and console.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR|Platform - On-Screen Keyboards and Text Input on Phones, Consoles and VR]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
