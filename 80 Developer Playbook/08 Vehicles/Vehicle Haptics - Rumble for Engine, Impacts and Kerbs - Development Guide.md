---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Vehicle Haptics - Rumble for Engine, Impacts and Kerbs.md"
---
# Vehicle Haptics - Rumble for Engine, Impacts and Kerbs — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Vehicle Haptics - Rumble for Engine, Impacts and Kerbs|Vehicle Haptics - Rumble for Engine, Impacts and Kerbs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Driving is the genre where controller rumble adds the most for the least work: a thud on a crash, a buzz on the rumble strip, a soft pulse at the rev limiter. Roblox now supports haptics on phones (most iPhone, Pixel and Galaxy devices), PlayStation and Xbox pads and Quest Touch controllers through `HapticEffect`, with the older `HapticService:SetMotor` still available for direct motor control.
**Useful source sections:** Two APIs, Crash thud (all devices), Engine and surface buzz (gamepad).

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Vehicle Haptics - Rumble for Engine, Impacts and Kerbs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Vehicle Haptics - Rumble for Engine, Impacts and Kerbs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Vehicle Haptics - Rumble for Engine, Impacts and Kerbs|Vehicle Haptics - Rumble for Engine, Impacts and Kerbs]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
