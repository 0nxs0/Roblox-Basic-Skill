---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Brain - Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax.md"
---
# Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Brain - Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax|Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A spawn director decides how many enemies a game can afford; a pacing director decides when to send them. Michael Booth's GDC 2009 talk "The AI Systems of Left 4 Dead" describes the classic algorithm: track how stressed each player is, push threats until stress peaks, then deliberately back off. The result is the rhythm Evolve's designers later described as quiet stretches followed by chaos. This note turns the...
**Useful source sections:** Step 1: an intensity value per player, Step 2: the director uses the maximum intensity, Step 3: four phases.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Brain - Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax|Adaptive Pacing with Player Intensity - Build Up, Peak, Fade and Relax]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
