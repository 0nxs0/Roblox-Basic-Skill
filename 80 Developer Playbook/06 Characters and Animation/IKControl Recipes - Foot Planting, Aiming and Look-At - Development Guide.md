---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Deep Dives/IKControl Recipes - Foot Planting, Aiming and Look-At.md"
---
# IKControl Recipes - Foot Planting, Aiming and Look-At — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Deep Dives/IKControl Recipes - Foot Planting, Aiming and Look-At|IKControl Recipes - Foot Planting, Aiming and Look-At]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
An `IKControl` must be a child of a `Humanoid` or an `AnimationController` that has an `Animator`. It is solved after animations each frame, so it corrects the animated pose rather than replacing it.
**Useful source sections:** 1. IKControl in 60 seconds, 2. Recipe: foot planting on slopes and stairs, 3. Recipe: look-at for heads (NPCs, dialogue, player).

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For IKControl Recipes - Foot Planting, Aiming and Look-At, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using IKControl Recipes - Foot Planting, Aiming and Look-At and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Deep Dives/IKControl Recipes - Foot Planting, Aiming and Look-At|IKControl Recipes - Foot Planting, Aiming and Look-At]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
