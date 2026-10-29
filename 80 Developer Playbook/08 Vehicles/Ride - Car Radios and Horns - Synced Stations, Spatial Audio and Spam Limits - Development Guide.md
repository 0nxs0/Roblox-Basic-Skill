---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits.md"
---
# Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits|Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A radio turns a car into a social space, and a horn is the most-used button in any roleplay city. Both are also the fastest way to annoy everyone on the server. Build them so the music is in the car (spatial, quiet from outside), stations are synced (everyone in the car hears the same second), and horns are rate limited and mutable.
**Useful source sections:** What can be played, Spatial setup (new Audio API), Station sync.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits|Ride - Car Radios and Horns - Synced Stations, Spatial Audio and Spam Limits]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
