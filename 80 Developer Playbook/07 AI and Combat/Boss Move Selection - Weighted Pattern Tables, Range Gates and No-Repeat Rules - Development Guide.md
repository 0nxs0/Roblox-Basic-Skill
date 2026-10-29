---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules.md"
---
# Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules|Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The boss design note covers phases and telegraphs; this note is about the brain that picks the next move. Most Roblox bosses use `moves[math.random(#moves)]`, which gives three slams in a row, a ranged attack while the player is hugging the boss, and no sense of personality. A move selector built from a few rules fixes that and stays data-driven, so designers can tune a boss without editing code.
**Useful source sections:** Move definition, Selection rules, in order, Scripted strings and signature sequences.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules|Boss Move Selection - Weighted Pattern Tables, Range Gates and No-Repeat Rules]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
