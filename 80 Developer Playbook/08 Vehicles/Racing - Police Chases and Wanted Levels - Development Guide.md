---
kind: development-companion
category: "08 Vehicles"
source-note: "08 Vehicles/Vehicles/Community Knowledge/Racing - Police Chases and Wanted Levels.md"
---
# Racing - Police Chases and Wanted Levels — Development Guide

New practical guidance for [[08 Vehicles/Vehicles/Community Knowledge/Racing - Police Chases and Wanted Levels|Racing - Police Chases and Wanted Levels]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Cops-and-robbers driving games (Jailbreak, Emergency Response, driving roleplay games) and street-racing games both run on a heat loop: break a rule, get noticed, escalate, escape or get busted. The loop needs three server systems: a heat value, a "who can see you" check, and a pursuit director that spawns or assigns chasers. Police vehicles themselves can reuse the AI driver from Racing - AI Racers on a Racing...
**Useful source sections:** 1. Heat as a number, stars as display, 2. Witnesses: line of sight, not magic, 3. Escape (cooldown) rules.

## Apply it
Use this topic as part of **tune vehicle handling repeatably**.
- **Define the contract:** For Racing - Police Chases and Wanted Levels, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set handling targets and tune one parameter at a time on a fixed course.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Account for network ownership, collisions, seat changes, uneven ground, and touch input.

## Validate before shipping
- **Expected path:** Build one small feature using Racing - Police Chases and Wanted Levels and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test stability, collisions, recovery, and multiple clients.

## Connected work
- Source note: [[08 Vehicles/Vehicles/Community Knowledge/Racing - Police Chases and Wanted Levels|Racing - Police Chases and Wanted Levels]]
- Category hub: [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles development hub]]
- Related disciplines: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
