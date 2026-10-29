---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Screen Orientation and Portrait Mode on Phones.md"
---
# Platform - Screen Orientation and Portrait Mode on Phones — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Screen Orientation and Portrait Mode on Phones|Platform - Screen Orientation and Portrait Mode on Phones]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox games run in landscape by default, which suits third-person action. But some genres play better held upright with one hand: idle and clicker games, card and puzzle games, social apps, minigames inside a bigger game. Roblox lets you pick or switch orientation per game and even mid-session. Doing it well means designing two layouts or committing to one and locking it.
**Useful source sections:** The five modes (`Enum.ScreenOrientation`), Where to set it, Designing for portrait.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Screen Orientation and Portrait Mode on Phones, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Screen Orientation and Portrait Mode on Phones and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Screen Orientation and Portrait Mode on Phones|Platform - Screen Orientation and Portrait Mode on Phones]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
