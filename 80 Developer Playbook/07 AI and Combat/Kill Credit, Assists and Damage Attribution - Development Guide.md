---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Kill Credit, Assists and Damage Attribution.md"
---
# Kill Credit, Assists and Damage Attribution — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Kill Credit, Assists and Damage Attribution|Kill Credit, Assists and Damage Attribution]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox does not track who killed whom; the DevForum answer is always "you have to record it yourself". The classic method from old Roblox gear is the creator tag: an `ObjectValue` named `creator` parented into the victim's Humanoid with `Value = attackerPlayer`, removed after a couple of seconds by Debris, and read in `Humanoid.Died`. It works for simple games, but it only remembers the last hitter, breaks when...
**Useful source sections:** The ledger, Attribution rules to decide, Rewards.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Kill Credit, Assists and Damage Attribution, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Kill Credit, Assists and Damage Attribution and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Kill Credit, Assists and Damage Attribution|Kill Credit, Assists and Damage Attribution]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
