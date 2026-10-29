---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Racing - Tuning Menus and Performance Index Balancing.md"
---
# Racing - Tuning Menus and Performance Index Balancing — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Racing - Tuning Menus and Performance Index Balancing|Racing - Tuning Menus and Performance Index Balancing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A tuning menu lets players feel like mechanics: more power, stiffer springs, different gearing. Without a balancing rule, though, every car ends up maxed and the class system dies. Real racing games solve this with a performance index (PI): one number per car that goes up with upgrades and decides which class it races in. This note shows a simple PI model, the tuning UI, and how settings reach the physics.
**Useful source sections:** 1. Two kinds of options, 2. Stats as attributes, 3. A simple PI formula.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Racing - Tuning Menus and Performance Index Balancing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Racing - Tuning Menus and Performance Index Balancing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Racing - Tuning Menus and Performance Index Balancing|Racing - Tuning Menus and Performance Index Balancing]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
