---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Frame Rate Caps and Frame-Rate-Independent Code.md"
---
# Platform - Frame Rate Caps and Frame-Rate-Independent Code — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Frame Rate Caps and Frame-Rate-Independent Code|Platform - Frame Rate Caps and Frame-Rate-Independent Code]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Different devices run your client at very different frame rates: a budget phone at 30, most devices at the default 60 cap, a gaming PC at up to 240, a Quest aiming for 72. Any code that assumes "one frame = 1/60 s" behaves differently on each: cameras turn faster on high-FPS PCs, lerps feel snappier, cooldown bars drain unevenly, and fixed per-frame forces give some players an advantage. This note lists the caps...
**Useful source sections:** Frame rates you will meet, Rule 1: scale by delta time, Rule 2: smoothing needs an exponential, not a fixed alpha.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Frame Rate Caps and Frame-Rate-Independent Code, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Frame Rate Caps and Frame-Rate-Independent Code and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Frame Rate Caps and Frame-Rate-Independent Code|Platform - Frame Rate Caps and Frame-Rate-Independent Code]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
