---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance.md"
---
# Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance|Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
On a phone, running out of memory does not slow the game down politely: the OS kills Roblox and the player sees their home screen. The design-for-performance docs call lower-end mobile devices "severely" memory-limited and prone to out-of-memory (OOM) crashes. Because the typical player is on such a device, client memory is the budget that decides whether your game is playable for most of your audience, not just...
**Useful source sections:** Who you are building for (Roblox's own numbers), Why your Studio numbers lie, Reading memory from code.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance|Platform - Memory Limits on Low-End Phones - Budgets and Crash Avoidance]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
