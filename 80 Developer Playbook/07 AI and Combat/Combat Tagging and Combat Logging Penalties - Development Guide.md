---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Combat Tagging and Combat Logging Penalties.md"
---
# Combat Tagging and Combat Logging Penalties — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Combat Tagging and Combat Logging Penalties|Combat Tagging and Combat Logging Penalties]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
In any game where death costs something (dropped loot, lost bounty, permadeath, rank), players about to lose a fight will simply leave. Their save is untouched and they rejoin elsewhere; the winner gets nothing. The DevForum tutorials on combat logging describe the standard fix in three parts: tag players when they fight, decide when a tag counts, and catch them when they leave while tagged. This note adds the...
**Useful source sections:** 1. Tag on the server, 2. Catch the leave, 3. Choose a penalty.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Combat Tagging and Combat Logging Penalties, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Combat Tagging and Combat Logging Penalties and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Combat Tagging and Combat Logging Penalties|Combat Tagging and Combat Logging Penalties]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
