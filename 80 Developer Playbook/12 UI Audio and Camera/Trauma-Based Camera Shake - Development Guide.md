---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Camera Game Feel/Community Knowledge/Trauma-Based Camera Shake.md"
---
# Trauma-Based Camera Shake — Development Guide

New practical guidance for [[12 UI Audio and Camera/Camera Game Feel/Community Knowledge/Trauma-Based Camera Shake|Trauma-Based Camera Shake]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most Roblox screen shake is `camera.CFrame = CFrame.new(math.random(), math.random(), 0)` for a few frames. It looks jittery, ignores frame rate, and several explosions at once either cancel out or go crazy. The "trauma" model, popularised by Squirrel Eiserloh's GDC 2016 math-for-cameras talk and since copied into Bevy, Godot and many other engines, fixes all three: events add trauma, trauma decays over time,...
**Useful source sections:** The model in four rules, Roblox implementation, Distance falloff for world events.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Trauma-Based Camera Shake, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Trauma-Based Camera Shake and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Camera Game Feel/Community Knowledge/Trauma-Based Camera Shake|Trauma-Based Camera Shake]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
