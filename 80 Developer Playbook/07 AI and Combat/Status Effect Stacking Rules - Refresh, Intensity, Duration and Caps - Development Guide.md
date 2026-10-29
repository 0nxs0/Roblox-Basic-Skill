---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Fight - Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps.md"
---
# Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Fight - Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps|Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"What happens when two players poison the same zombie?" is the question that breaks most status systems. Without a written rule, the second poison either overwrites the first, doubles damage forever, or leaves a stray `task.delay` that removes the effect early. Big games make the rule explicit per effect. Guild Wars 2 is the clearest public example: every boon and condition is marked as stacking in intensity or...
**Useful source sections:** The five stacking modes, Hard rules worth copying, Data shape.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Fight - Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps|Status Effect Stacking Rules - Refresh, Intensity, Duration and Caps]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
