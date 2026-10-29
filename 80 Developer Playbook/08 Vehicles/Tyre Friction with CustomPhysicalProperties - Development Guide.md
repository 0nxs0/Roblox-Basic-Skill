---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Tyre Friction with CustomPhysicalProperties.md"
---
# Tyre Friction with CustomPhysicalProperties — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Tyre Friction with CustomPhysicalProperties|Tyre Friction with CustomPhysicalProperties]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
On a constraint car, grip is not a "grip" property: it is the friction between the wheel part and whatever it touches. Roblox blends the two parts' friction with a weighted average, which means the road can override your tyres unless you set weights on purpose. Understanding that one formula explains ice levels that do nothing, drift cars that will not drift and wheels that grip walls.
**Useful source sections:** The formula (from the PhysicalProperties docs), Setting it in code, Surface design patterns.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Tyre Friction with CustomPhysicalProperties, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Tyre Friction with CustomPhysicalProperties and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Tyre Friction with CustomPhysicalProperties|Tyre Friction with CustomPhysicalProperties]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
