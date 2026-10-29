---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring.md"
---
# Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring|Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Boards are the most "movement game" of all vehicles: speed comes from skill, and score comes from tricks. Roblox once shipped a built-in `SkateboardPlatform` (with a `SkateboardController`); the API reference marks `SkateboardPlatform` deprecated and no longer supported, so build your own. The good news: a board is best treated as a character movement mode, not a physics vehicle.
**Useful source sections:** Board as a movement mode, Ollie and air, Grinding rails.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring|Ride - Skateboards and Hoverboards - Ollies, Grinds and Trick Scoring]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
