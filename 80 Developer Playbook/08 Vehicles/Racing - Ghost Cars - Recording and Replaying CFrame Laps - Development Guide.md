---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Racing - Ghost Cars - Recording and Replaying CFrame Laps.md"
---
# Racing - Ghost Cars - Recording and Replaying CFrame Laps — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Racing - Ghost Cars - Recording and Replaying CFrame Laps|Racing - Ghost Cars - Recording and Replaying CFrame Laps]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A ghost car (your best lap, a friend's lap, or the world record driven as a see-through car) is the single best feature for time-trial retention: it gives players a target they can see. On Roblox it is cheap, because you do not replay physics, you replay positions. DevForum advice for vehicle replays agrees: only record the root part of the vehicle, never every part.
**Useful source sections:** What to record, Recording on the client, keeping it light, Who records: client or server?.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Racing - Ghost Cars - Recording and Replaying CFrame Laps, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Racing - Ghost Cars - Recording and Replaying CFrame Laps and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Racing - Ghost Cars - Recording and Replaying CFrame Laps|Racing - Ghost Cars - Recording and Replaying CFrame Laps]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
