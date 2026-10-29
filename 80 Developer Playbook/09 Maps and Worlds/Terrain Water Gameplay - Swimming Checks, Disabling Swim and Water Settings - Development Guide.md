---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings.md"
---
# Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings — Development Guide

New practical guidance for [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings|Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Terrain water gives you free swimming, buoyancy and a decent surface shader, which is why most lakes and oceans on Roblox are terrain. Gameplay around water is less free: drowning timers, "lava-like" deadly water, fishing spots, boats that need to know they are afloat, and maps where swimming should be disabled. Touch events do not help here, because terrain is one object. This note gathers the techniques that work.
**Useful source sections:** Water settings (Terrain properties), Detecting "is this character in water", Disabling swimming.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings|Terrain Water Gameplay - Swimming Checks, Disabling Swim and Water Settings]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
