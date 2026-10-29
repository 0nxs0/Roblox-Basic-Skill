---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Parry, Block and Guard Break - Timing Windows Over the Network.md"
---
# Parry, Block and Guard Break - Timing Windows Over the Network — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Parry, Block and Guard Break - Timing Windows Over the Network|Parry, Block and Guard Break - Timing Windows Over the Network]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Anime battlegrounds and sword games live or die on defense. A block that never fails makes fights stall; a parry that works only on 20 ms ping makes mobile players quit. The DevForum threads agree on the basics: the server holds a timed block/parry state, and hit resolution checks that state before applying damage. This note fills in what the threads leave open: window lengths, latency handling, block meter and...
**Useful source sections:** States, Server-side state, Latency: who gets the benefit?.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Parry, Block and Guard Break - Timing Windows Over the Network, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Parry, Block and Guard Break - Timing Windows Over the Network and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Parry, Block and Guard Break - Timing Windows Over the Network|Parry, Block and Guard Break - Timing Windows Over the Network]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
