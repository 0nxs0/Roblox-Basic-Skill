---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts.md"
---
# Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts|Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Not everything that moves needs a Humanoid or a tween. A treasure chest that creaks open with a bounce, a vending machine that shakes, a drawbridge, a four-legged creature, a flag: all of these can be keyframed in the Animation Editor and played with an `AnimationController`. You get easing, markers, blending and priorities for free, and the Humanoid's physics and state machine cost goes away.
**Useful source sections:** When to pick what, Rig a prop in five steps, Playing it.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts|Anim - Animating Props and Creatures with AnimationController - Doors, Chests and Beasts]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
