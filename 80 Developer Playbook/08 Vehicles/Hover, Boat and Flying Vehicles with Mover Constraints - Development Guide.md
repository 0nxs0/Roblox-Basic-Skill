---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Deep Dives/Hover, Boat and Flying Vehicles with Mover Constraints.md"
---
# Hover, Boat and Flying Vehicles with Mover Constraints — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Deep Dives/Hover, Boat and Flying Vehicles with Mover Constraints|Hover, Boat and Flying Vehicles with Mover Constraints]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Ownership: as with cars, the driver's client owns the assembly and runs the controller. See Vehicle jitters - wrong player controls physics.
**Useful source sections:** 1. Mover constraints cheat sheet (current API), 2. Hoverbike, 3. Boats.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Hover, Boat and Flying Vehicles with Mover Constraints, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Hover, Boat and Flying Vehicles with Mover Constraints and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Deep Dives/Hover, Boat and Flying Vehicles with Mover Constraints|Hover, Boat and Flying Vehicles with Mover Constraints]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
