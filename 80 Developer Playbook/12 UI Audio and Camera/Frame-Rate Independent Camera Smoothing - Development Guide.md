---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Camera Game Feel/Community Knowledge/Frame-Rate Independent Camera Smoothing.md"
---
# Frame-Rate Independent Camera Smoothing — Development Guide

New practical guidance for [[12 UI Audio and Camera/Camera Game Feel/Community Knowledge/Frame-Rate Independent Camera Smoothing|Frame-Rate Independent Camera Smoothing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox players run anywhere from 30 FPS on old phones to 240 FPS on gaming PCs (with the FPS cap raised). The common smoothing line `pos = pos:Lerp(target, 0.1)` runs once per frame, so on a 240 FPS machine the camera catches up eight times faster than at 30 FPS. Your carefully tuned follow cam feels floaty on phones and twitchy on PCs. The fix is one formula: use an exponential decay factor based on delta time.
**Useful source sections:** The formula, Typical rates for cameras, Rotation: lerp the CFrame, not the angles.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Frame-Rate Independent Camera Smoothing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Frame-Rate Independent Camera Smoothing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Camera Game Feel/Community Knowledge/Frame-Rate Independent Camera Smoothing|Frame-Rate Independent Camera Smoothing]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
