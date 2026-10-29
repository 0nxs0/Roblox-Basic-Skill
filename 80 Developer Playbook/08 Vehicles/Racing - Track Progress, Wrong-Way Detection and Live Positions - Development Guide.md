---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Racing - Track Progress, Wrong-Way Detection and Live Positions.md"
---
# Racing - Track Progress, Wrong-Way Detection and Live Positions — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Racing - Track Progress, Wrong-Way Detection and Live Positions|Racing - Track Progress, Wrong-Way Detection and Live Positions]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The gate-crossing system in Kart Racing Systems - Checkpoints, Laps, Boost Pads and Respawn decides whether a lap counts. This note covers the second job: one smooth "progress" number per racer that drives live positions, the "WRONG WAY" banner, gap times and shortcut flags. A good progress value makes the HUD feel honest; a bad one makes 2nd and 3rd flicker every frame on long straights.
**Useful source sections:** One number for the whole race, Better fraction: project onto the segment, not straight-line distance, Wrong-way detection.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Racing - Track Progress, Wrong-Way Detection and Live Positions, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Racing - Track Progress, Wrong-Way Detection and Live Positions and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Racing - Track Progress, Wrong-Way Detection and Live Positions|Racing - Track Progress, Wrong-Way Detection and Live Positions]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
