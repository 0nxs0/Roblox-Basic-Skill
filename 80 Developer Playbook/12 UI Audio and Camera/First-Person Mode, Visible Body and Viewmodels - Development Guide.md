---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Camera Game Feel/Community Knowledge/First-Person Mode, Visible Body and Viewmodels.md"
---
# First-Person Mode, Visible Body and Viewmodels — Development Guide

New practical guidance for [[12 UI Audio and Camera/Camera Game Feel/Community Knowledge/First-Person Mode, Visible Body and Viewmodels|First-Person Mode, Visible Body and Viewmodels]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Shooters, horror games and immersive sims usually want first person. Roblox gives a basic version for free (`CameraMode = LockFirstPerson`), but out of the box the body disappears, tools float, and the camera sits inside the head. There are two common upgrades: a true first-person body (you see your own legs and arms) and a viewmodel (a separate arms-and-weapon model drawn in front of the camera, like most FPS...
**Useful source sections:** Step 1: lock first person, Step 2a: showing your own body, Step 2b: viewmodel arms.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For First-Person Mode, Visible Body and Viewmodels, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using First-Person Mode, Visible Body and Viewmodels and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Camera Game Feel/Community Knowledge/First-Person Mode, Visible Body and Viewmodels|First-Person Mode, Visible Body and Viewmodels]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
