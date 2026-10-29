---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression.md"
---
# Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression|Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Ten enemies that all attack the player at once feel unfair and look dumb (they clump into one blob). Action games solve this with an attack token pool: an enemy must hold a token to attack, and only a few tokens exist. DOOM (2016) used this for its demons: each attack type had a limited number of tokens at a time, demons requested a token before attacking and released it after, difficulty settings changed the...
**Useful source sections:** Token pool design, What token-less enemies do, Squad feel without a squad brain.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression|Attack Tokens and Squad Roles - Limiting Attackers, Flanking and Suppression]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
