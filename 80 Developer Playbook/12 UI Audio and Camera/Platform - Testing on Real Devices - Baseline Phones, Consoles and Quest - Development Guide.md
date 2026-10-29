---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest.md"
---
# Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest|Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Studio's Device Emulator and Controller Emulator catch layout and binding mistakes fast (see Device, Network and Controller Simulation Test Pass). They cannot show you memory pressure, thermal throttling, touch latency, a TV's cropped edges or how your sound mix holds up on a phone speaker. Roblox's own guide puts it bluntly: if you only test on your development machine, "you're testing for the minority of your...
**Useful source sections:** Pick a baseline device first, A lab that fits a small budget, What to check on hardware (from the docs, condensed).

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest|Platform - Testing on Real Devices - Baseline Phones, Consoles and Quest]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
