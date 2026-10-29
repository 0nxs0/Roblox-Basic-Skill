---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players.md"
---
# Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players|Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Drop-in battle royales, sky islands and plane jumps all need a "falling but controlled" state. The default Humanoid falls at full gravity with almost no air control. The fix is one `VectorForce` on the HumanoidRootPart that applies drag and lift depending on the current gear: none, skydive, wingsuit, parachute or paraglider. Each gear is just a different set of numbers.
**Useful source sections:** The force, Gear table (starting numbers, tune), State machine.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players|Ride - Parachutes, Paragliders and Wingsuits - Drag States for Falling Players]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
