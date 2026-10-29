---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/Tower Defense Targeting Modes - First, Last, Strongest and Closest.md"
---
# Tower Defense Targeting Modes - First, Last, Strongest and Closest — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/Tower Defense Targeting Modes - First, Last, Strongest and Closest|Tower Defense Targeting Modes - First, Last, Strongest and Closest]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Tower defense is one of Roblox's biggest genres, and "my tower shoots the wrong enemy" is one of its most common DevForum threads. The bug is almost always the same: "First" was implemented as "closest to the tower" or "first child in the Enemies folder", which looks right on straight paths and breaks the moment the path turns a corner. The fix is to track path progress per enemy and build every targeting mode...
**Useful source sections:** Track progress, not position, The modes, Doing it at scale.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Tower Defense Targeting Modes - First, Last, Strongest and Closest, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Tower Defense Targeting Modes - First, Last, Strongest and Closest and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/Tower Defense Targeting Modes - First, Last, Strongest and Closest|Tower Defense Targeting Modes - First, Last, Strongest and Closest]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
