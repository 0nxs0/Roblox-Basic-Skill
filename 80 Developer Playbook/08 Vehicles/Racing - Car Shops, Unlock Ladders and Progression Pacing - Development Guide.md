---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Racing - Car Shops, Unlock Ladders and Progression Pacing.md"
---
# Racing - Car Shops, Unlock Ladders and Progression Pacing — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Racing - Car Shops, Unlock Ladders and Progression Pacing|Racing - Car Shops, Unlock Ladders and Progression Pacing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In driving games the car list is the progression. Players stay for "the next car", so the shop needs a clear ladder, prices that match earning rates, and ownership stored safely. Paint/parts customisation and loadout saving are covered in Vehicle Customisation - Paint, Parts and Saved Loadouts; this note is buying and unlocking whole cars.
**Useful source sections:** 1. A car catalogue as data, 2. Pace prices from earning rates, 3. Mix of gates.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Racing - Car Shops, Unlock Ladders and Progression Pacing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Racing - Car Shops, Unlock Ladders and Progression Pacing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Racing - Car Shops, Unlock Ladders and Progression Pacing|Racing - Car Shops, Unlock Ladders and Progression Pacing]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
