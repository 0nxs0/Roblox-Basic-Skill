---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Adaptive Quality Governor Driven by Frame Time.md"
---
# Platform - Adaptive Quality Governor Driven by Frame Time — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Adaptive Quality Governor Driven by Frame Time|Platform - Adaptive Quality Governor Driven by Frame Time]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox already scales its own rendering with the automatic quality system, but it cannot know which of your effects are optional: the extra debris, the fake god rays, the 40 ambient NPCs. A small client-side governor that watches frame time and switches your own effect tiers keeps phones smooth in busy moments without making high-end PCs look worse. This is the code side of the tier plan in Visual Scalability and...
**Useful source sections:** Design, Implementation, What each tier can drop (cheapest loss first).

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Adaptive Quality Governor Driven by Frame Time, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Adaptive Quality Governor Driven by Frame Time and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Adaptive Quality Governor Driven by Frame Time|Platform - Adaptive Quality Governor Driven by Frame Time]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
