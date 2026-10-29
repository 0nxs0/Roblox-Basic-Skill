---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Fight - Damage Formula Pipeline - Armor, Penetration, Resistances and Crits.md"
---
# Damage Formula Pipeline - Armor, Penetration, Resistances and Crits — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Fight - Damage Formula Pipeline - Armor, Penetration, Resistances and Crits|Damage Formula Pipeline - Armor, Penetration, Resistances and Crits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most Roblox games start with `humanoid:TakeDamage(10)` scattered across twenty scripts. The day you add armor, a crit stat or a fire resistance pet, every one of those calls is wrong in a different way. Games with long-lived stat systems (MOBAs, RPGs, Minecraft) all run damage through one ordered pipeline with a published formula. This note gives you a pipeline you can copy and the math to balance it.
**Useful source sections:** The pipeline (one server function, fixed order), Armor: use the "100 / (100 + armor)" curve, Penetration order.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Damage Formula Pipeline - Armor, Penetration, Resistances and Crits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Damage Formula Pipeline - Armor, Penetration, Resistances and Crits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Fight - Damage Formula Pipeline - Armor, Penetration, Resistances and Crits|Damage Formula Pipeline - Armor, Penetration, Resistances and Crits]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
