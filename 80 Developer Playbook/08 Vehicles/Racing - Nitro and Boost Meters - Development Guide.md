---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Racing - Nitro and Boost Meters.md"
---
# Racing - Nitro and Boost Meters — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Racing - Nitro and Boost Meters|Racing - Nitro and Boost Meters]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Boost pads and drift mini-turbos are one-shot impulses (see Arcade Handling and Drifting Without Fighting Physics). A nitro meter is a resource the player manages: it fills from good driving and drains while held. It adds a decision ("use it now on the straight or save it for the overtake?") and is the main reason players learn a track. This note covers meter rules, applying the force and keeping it exploit-proof.
**Useful source sections:** Meter design choices, What fills the meter, Applying the boost.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Racing - Nitro and Boost Meters, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Racing - Nitro and Boost Meters and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Racing - Nitro and Boost Meters|Racing - Nitro and Boost Meters]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
