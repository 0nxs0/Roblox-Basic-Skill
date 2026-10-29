---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Deep Dives/Animation Markers for Hit Frames, Footsteps and Sync.md"
---
# Animation Markers for Hit Frames, Footsteps and Sync — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Deep Dives/Animation Markers for Hit Frames, Footsteps and Sync|Animation Markers for Hit Frames, Footsteps and Sync]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In the Animation Editor you can add Animation Events on the timeline. Each event has a name (for example `HitStart`) and an optional parameter string (for example `"blade,heavy"`). At runtime you listen for them with:
**Useful source sections:** 1. What markers are (and what they are not), 2. A naming convention that scales, 3. Client side: markers drive presentation and requests.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Animation Markers for Hit Frames, Footsteps and Sync, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Animation Markers for Hit Frames, Footsteps and Sync and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Deep Dives/Animation Markers for Hit Frames, Footsteps and Sync|Animation Markers for Hit Frames, Footsteps and Sync]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
