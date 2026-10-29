---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager.md"
---
# Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager|Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Classic Humanoid movement is instant: full speed on the first frame of input, dead stop on release, near-total steering in the air. That suits obbies, but a horror game, a heavy knight or a skating game needs weight. Roblox's physics controllers (`ControllerManager` with `GroundController`, `AirController` and friends, also what the Character Controller Library runs on) expose the exact knobs: acceleration time,...
**Useful source sections:** The knobs that matter, Starting presets (our suggestions, tune by playtest), Script shape.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager|Anim - Movement Feel Tuning - Acceleration, Turn Speed and Air Control with ControllerManager]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
