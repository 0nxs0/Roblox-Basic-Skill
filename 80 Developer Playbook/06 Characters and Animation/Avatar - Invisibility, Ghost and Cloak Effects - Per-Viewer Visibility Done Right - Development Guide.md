---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right.md"
---
# Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right|Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Stealth abilities, spectator ghosts, a Predator-style cloak, a "dead players become ghosts" mode: all of them come down to hiding a character fully or partly, sometimes only from some viewers. The naive version (loop the character, set `Transparency = 1`) misses faces, accessories, nametags, shadows and footsteps, and it cannot show teammates a faint outline while enemies see nothing.
**Useful source sections:** Everything that can give a player away, Same for everyone vs per viewer, Ghost and cloak looks.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right|Avatar - Invisibility, Ghost and Cloak Effects - Per-Viewer Visibility Done Right]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
