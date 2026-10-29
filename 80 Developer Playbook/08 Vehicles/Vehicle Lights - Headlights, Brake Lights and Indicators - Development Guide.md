---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Vehicle Lights - Headlights, Brake Lights and Indicators.md"
---
# Vehicle Lights - Headlights, Brake Lights and Indicators — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Vehicle Lights - Headlights, Brake Lights and Indicators|Vehicle Lights - Headlights, Brake Lights and Indicators]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Working lights are the cheapest polish a vehicle can get, and at night they are gameplay: players read other cars by their lights. They are also a classic performance trap, because every car with four shadow-casting lights adds up fast on phones. This note covers a light rig that looks good and scales.
**Useful source sections:** Two layers: glow and light, Headlights, Brake and reverse lights from inputs.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Vehicle Lights - Headlights, Brake Lights and Indicators, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Vehicle Lights - Headlights, Brake Lights and Indicators and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Vehicle Lights - Headlights, Brake Lights and Indicators|Vehicle Lights - Headlights, Brake Lights and Indicators]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
