---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Explosions - Radius Damage, Falloff and Cover Checks.md"
---
# Explosions - Radius Damage, Falloff and Cover Checks — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Explosions - Radius Damage, Falloff and Cover Checks|Explosions - Radius Damage, Falloff and Cover Checks]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Grenades, rockets, barrels and boss slams all need area damage. Roblox's built-in `Explosion` instance is convenient but its default behavior kills any Humanoid in range by breaking joints, ignores walls, and fires `Hit` once per part, so a character can be "hit" 15 times. The Explosion reference itself recommends turning the destructive parts off and applying your own damage through `Hit`. This note shows that...
**Useful source sections:** The built-in Explosion, tamed, A custom version (more control, fewer surprises), Knockback.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Explosions - Radius Damage, Falloff and Cover Checks, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Explosions - Radius Damage, Falloff and Cover Checks and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Explosions - Radius Damage, Falloff and Cover Checks|Explosions - Radius Damage, Falloff and Cover Checks]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
