---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing.md"
---
# Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing|Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Police chases in city RP games, rival racers, a monster truck hunting players: all need an AI that steers toward a moving target and stays fun to escape or beat. Two classic sources cover it: Craig Reynolds' "Steering Behaviors for Autonomous Characters" (GDC 1999) for pursuit math, and Eduardo Jimenez's Game Developer article on the AI of Pure (Black Rock Studio) for keeping AI racers competitive without obvious...
**Useful source sections:** 1. Pursuit: aim where the target will be, 2. Path first, steering second, 3. Police chase design.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing|Chase AI for Vehicles and Racers - Pursuit Prediction and Skill Balancing]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
