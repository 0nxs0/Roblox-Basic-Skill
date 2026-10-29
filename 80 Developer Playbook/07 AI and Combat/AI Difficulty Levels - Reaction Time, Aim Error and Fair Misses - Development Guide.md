---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses.md"
---
# AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses|AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
On Roblox, server-side NPCs can aim perfectly: they know every player's position exactly and can raycast in the same frame. A shooter enemy with perfect aim is not hard, it is unfair, and players feel it immediately. Difficulty should come from human-like limits that you dial up and down, not from more HP and damage. The sources below agree on a short list of knobs.
**Useful source sections:** The knobs, Fair misses, Implementation on Roblox.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses|AI Difficulty Levels - Reaction Time, Aim Error and Fair Misses]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
