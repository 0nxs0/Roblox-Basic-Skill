---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/HingeConstraint Motors and Servos for Wheels and Steering.md"
---
# HingeConstraint Motors and Servos for Wheels and Steering — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/HingeConstraint Motors and Servos for Wheels and Steering|HingeConstraint Motors and Servos for Wheels and Steering]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Almost every physics car on Roblox is two kinds of actuator: motors that spin the drive wheels and servos that turn the steering knuckles to an angle. Both live on `HingeConstraint` (and on the angular half of `CylindricalConstraint`). Most "car is sluggish / car flips / steering wobbles" problems come from leaving their limits at defaults or from mixing up units.
**Useful source sections:** ActuatorType in one table, Drive wheels (Motor), Steering (Servo).

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For HingeConstraint Motors and Servos for Wheels and Steering, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using HingeConstraint Motors and Servos for Wheels and Steering and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/HingeConstraint Motors and Servos for Wheels and Steering|HingeConstraint Motors and Servos for Wheels and Steering]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
