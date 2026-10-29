---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Downed, Revive and Bleed-Out States.md"
---
# Downed, Revive and Bleed-Out States — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Downed, Revive and Bleed-Out States|Downed, Revive and Bleed-Out States]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Co-op shooters and zombie survival games feel much better when a player at zero health goes down instead of dying instantly: teammates get a rescue moment, mistakes are recoverable, and dying alone in a corner becomes a story. Battle royales call it DBNO ("down but not out"); in PUBG the bleed-out timer pauses while a teammate is reviving; in Fortnite teammates hold an interact button near the downed player....
**Useful source sections:** Rule 1: never let Health reach 0, Rule 2: the downed state, Rule 3: reviving.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Downed, Revive and Bleed-Out States, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Downed, Revive and Bleed-Out States and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Downed, Revive and Bleed-Out States|Downed, Revive and Bleed-Out States]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
