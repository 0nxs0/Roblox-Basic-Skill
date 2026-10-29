---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth.md"
---
# Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth|Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A submarine is a boat that must also be able to not float. On Roblox that means you control buoyancy instead of letting terrain water push you up forever. Players expect three things: dive and surface on command, stay at a chosen depth without fighting the controls, and feel danger the deeper they go. All three are cheap to build once you separate "how heavy am I" (ballast) from "how do I hold a depth" (a...
**Useful source sections:** How real subs do it (and what to copy), Roblox building blocks, Ballast as a 0-1 value.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth|Ride - Submarines - Ballast Tanks, Depth Hold and Crush Depth]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
