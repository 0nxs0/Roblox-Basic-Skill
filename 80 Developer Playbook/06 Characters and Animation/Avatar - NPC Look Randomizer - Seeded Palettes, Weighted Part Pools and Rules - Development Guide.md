---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules.md"
---
# Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules|Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Shopkeepers, townsfolk, survivors, zombies, crowd fans: games need dozens of NPCs that look different but still belong to the same world. Hand-dressing each one does not scale, and pure `math.random` on every slot produces clowns (neon pants, three hats, a tiny head on a giant body). A good randomizer is data + weights + rules + a seed: art direction stays in a table, and each NPC id always rebuilds the same look.
**Useful source sections:** The data table, The builder, Rules that stop clown outfits.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules|Avatar - NPC Look Randomizer - Seeded Palettes, Weighted Part Pools and Rules]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
