---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Headshots and Hit Zones - Damage Multipliers and Accessory Hits.md"
---
# Headshots and Hit Zones - Damage Multipliers and Accessory Hits — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Headshots and Hit Zones - Damage Multipliers and Accessory Hits|Headshots and Hit Zones - Damage Multipliers and Accessory Hits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Hit zones turn aim into skill: headshots reward precision, limb hits soften spray. The common DevForum version is a raycast gun that checks `result.Instance.Name == "Head"` and doubles damage. It works until a player wears a big hat or hair (the ray hits the accessory's Handle, not the Head), an R6 rig names parts differently from R15, or a custom NPC has no "Head" at all. This note gives a robust zone lookup and...
**Useful source sections:** Map parts to zones, do not compare names everywhere, Should accessories count?, Server validation.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Headshots and Hit Zones - Damage Multipliers and Accessory Hits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Headshots and Hit Zones - Damage Multipliers and Accessory Hits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Headshots and Hit Zones - Damage Multipliers and Accessory Hits|Headshots and Hit Zones - Damage Multipliers and Accessory Hits]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
