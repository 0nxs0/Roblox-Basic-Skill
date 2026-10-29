---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors.md"
---
# Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors|Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Police vs criminals, red vs blue, prisoners in orange: team games usually need to force a uniform while still letting players keep their face and body. Classic `Shirt` and `Pants` images are still the cheapest way to do it: one texture each, no extra geometry, and they work on R6 and R15. The hard part is dealing with the player's own layered clothing and body colours on top.
**Useful source sections:** Two ways to apply a uniform, One uniform, many teams: tint it, Layered clothing hides classic clothing.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors|Team Uniforms and Skin Tones by Script - Shirt, Pants and BodyColors]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
