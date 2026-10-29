---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Seat Entry with ProximityPrompt - No More Accidental Sits.md"
---
# Seat Entry with ProximityPrompt - No More Accidental Sits — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Seat Entry with ProximityPrompt - No More Accidental Sits|Seat Entry with ProximityPrompt - No More Accidental Sits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
By default, touching a `Seat` or `VehicleSeat` welds the character in. Players get sucked into cars they walk past, trolls drive other people's cars, and on mobile there is no clear "get in" action. Every polished vehicle game replaces touch-to-sit with a deliberate prompt. The pattern is small and robust.
**Useful source sections:** The pattern, Prompt settings that help, Exiting.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Seat Entry with ProximityPrompt - No More Accidental Sits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Seat Entry with ProximityPrompt - No More Accidental Sits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Seat Entry with ProximityPrompt - No More Accidental Sits|Seat Entry with ProximityPrompt - No More Accidental Sits]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
