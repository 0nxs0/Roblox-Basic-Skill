---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Deep Dives/Animator Priorities, Weights and Blending Done Right.md"
---
# Animator Priorities, Weights and Blending Done Right — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Deep Dives/Animator Priorities, Weights and Blending Done Right|Animator Priorities, Weights and Blending Done Right]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
An `Animator` (under a `Humanoid` or an `AnimationController`) evaluates every playing `AnimationTrack` each frame. For each joint, it looks at the tracks that actually key that joint. The track with the highest `Priority` wins that joint. If several tracks share the top priority, their poses are blended by `WeightCurrent`. A track only affects joints that have keyframes in the clip, so an "upper body only"...
**Useful source sections:** 1. The mental model in one paragraph, 2. The priority ladder (current enum), 3. Load once, cache, reuse.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Animator Priorities, Weights and Blending Done Right, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Animator Priorities, Weights and Blending Done Right and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Deep Dives/Animator Priorities, Weights and Blending Done Right|Animator Priorities, Weights and Blending Done Right]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
