---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale.md"
---
# Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale|Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The same Roblox game is shown on a 5-inch phone held at arm's length, a 27-inch monitor at 60 cm and a 65-inch TV across the room. Pure Scale sizing (a panel at 75% width) looks fine on a monitor, cramped on a phone and gigantic on a 4K TV, as the cross-platform docs point out. The fix is to classify the screen, pick a layout per class, and scale within that layout. The vault's Responsive UI Layouts -...
**Useful source sections:** Signals you can read, No-code option: style queries, Script option: one layout controller.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale|Platform - Screen Size Classes - ViewportDisplaySize, Breakpoints and UIScale]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
