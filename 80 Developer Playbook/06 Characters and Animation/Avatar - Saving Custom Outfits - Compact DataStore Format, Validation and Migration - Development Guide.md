---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration.md"
---
# Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration — Development Guide

New practical guidance for [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration|Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Games with their own wardrobe (roleplay clothes, class armour, unlockable hats) must save what each player wears and owns. The tempting shortcut is to serialise the whole `HumanoidDescription` (every asset ID and colour) into the data store. That bloats save data, breaks when you change an asset, and lets a crafted request "wear" anything. Save item keys from your own catalog, not raw asset IDs, and rebuild the...
**Useful source sections:** Your catalog is the source of truth, Save format, Build on the server.

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Characters Customization/Community Knowledge/Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration|Avatar - Saving Custom Outfits - Compact DataStore Format, Validation and Migration]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
