---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Fight - Time-to-Kill Math and the Weapon Balance Sheet.md"
---
# Time-to-Kill Math and the Weapon Balance Sheet — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Fight - Time-to-Kill Math and the Weapon Balance Sheet|Time-to-Kill Math and the Weapon Balance Sheet]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Time to kill (TTK) is the single number that defines how a shooter feels. Low TTK (under 0.4 s) makes positioning and first shot decisive, like Call of Duty; high TTK (1 s and up) gives time to react, strafe and heal, like arena shooters and most Roblox anime/sim PvP. Siege.gg's Black Ops 7 guide quotes rough averages of 0.30-0.40 s for strong assault rifles and 0.25-0.35 s for close-range SMGs. If you never...
**Useful source sections:** The core formulas, Accuracy-adjusted TTK, Damage falloff.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Time-to-Kill Math and the Weapon Balance Sheet, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Time-to-Kill Math and the Weapon Balance Sheet and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Fight - Time-to-Kill Math and the Weapon Balance Sheet|Time-to-Kill Math and the Weapon Balance Sheet]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
