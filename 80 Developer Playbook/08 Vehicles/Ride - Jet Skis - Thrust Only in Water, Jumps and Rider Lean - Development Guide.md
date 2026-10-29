---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean.md"
---
# Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean|Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A jet ski is small, twitchy and fun because it reacts to waves and jumps off them. The big rule that separates a good one from a flying sofa: a water jet only pushes while its intake is in water. If thrust keeps working in the air, players fly off every wave and steer mid-air. Get that one rule right and the rest is tuning.
**Useful source sections:** Parts layout, Thrust gated by the intake, Steering.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean|Ride - Jet Skis - Thrust Only in Water, Jumps and Rider Lean]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
