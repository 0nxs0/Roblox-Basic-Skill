---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - VR Support Basics - VRService, UserCFrame and HeadScale.md"
---
# Platform - VR Support Basics - VRService, UserCFrame and HeadScale — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - VR Support Basics - VRService, UserCFrame and HeadScale|Platform - VR Support Basics - VRService, UserCFrame and HeadScale]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox runs on Meta Quest and PC VR headsets through OpenXR, so the same game works on both (VR guidelines). Most games get a playable VR mode for free from the default camera and controls; what breaks is anything custom: a scripted camera, a gun that only aims with the mouse, a ScreenGui covering the view. This note lists the APIs that tell you where the player's head and hands are, and the switches that change...
**Useful source sections:** Is the player in VR?, Head and hand tracking, Scale: how big the world feels.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - VR Support Basics - VRService, UserCFrame and HeadScale, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - VR Support Basics - VRService, UserCFrame and HeadScale and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - VR Support Basics - VRService, UserCFrame and HeadScale|Platform - VR Support Basics - VRService, UserCFrame and HeadScale]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
