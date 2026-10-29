---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Deep Dives/Combo Systems and Input Buffering.md"
---
# Combo Systems and Input Buffering — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Deep Dives/Combo Systems and Input Buffering|Combo Systems and Input Buffering]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
All of these are times on the attack clip. Export them from animation markers so they never drift (see Animation Markers for Hit Frames, Footsteps and Sync).
**Useful source sections:** 1. Vocabulary (use these words in your data), 2. The attack graph as data, 3. The input buffer.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Combo Systems and Input Buffering, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Combo Systems and Input Buffering and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Deep Dives/Combo Systems and Input Buffering|Combo Systems and Input Buffering]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
