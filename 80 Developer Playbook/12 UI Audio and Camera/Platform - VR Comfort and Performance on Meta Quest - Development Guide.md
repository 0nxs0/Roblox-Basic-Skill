---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - VR Comfort and Performance on Meta Quest.md"
---
# Platform - VR Comfort and Performance on Meta Quest — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - VR Comfort and Performance on Meta Quest|Platform - VR Comfort and Performance on Meta Quest]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In VR, a frame drop or a camera that moves without the player's body is not just ugly: it makes people feel sick and quit. Standalone headsets like the Quest render two images on a mobile chipset, so VR is both the most comfort-sensitive and one of the most performance-limited platforms Roblox supports. This note combines Roblox's VR guidelines with Meta's own locomotion guidance.
**Useful source sections:** What Roblox already does for comfort, Meta's locomotion guidance, applied to Roblox, Performance targets.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - VR Comfort and Performance on Meta Quest, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - VR Comfort and Performance on Meta Quest and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - VR Comfort and Performance on Meta Quest|Platform - VR Comfort and Performance on Meta Quest]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
