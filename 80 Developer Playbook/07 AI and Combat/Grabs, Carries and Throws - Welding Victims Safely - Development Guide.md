---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Fight - Grabs, Carries and Throws - Welding Victims Safely.md"
---
# Grabs, Carries and Throws - Welding Victims Safely — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Fight - Grabs, Carries and Throws - Welding Victims Safely|Grabs, Carries and Throws - Welding Victims Safely]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Grab moves (command grabs, carry-to-execute, picking up a downed teammate, throwing an enemy into a wall) are some of the most satisfying moves in battlegrounds and brawlers, and some of the most bug-prone on Roblox. Two characters become one physics assembly, network ownership moves, and the victim's Humanoid fights the weld. DevForum threads collect the working recipes and the traps.
**Useful source sections:** How the engine sees a grab, Recipe (server-side), Throw tech and counterplay (fighting-game convention).

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Grabs, Carries and Throws - Welding Victims Safely, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Grabs, Carries and Throws - Welding Victims Safely and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Fight - Grabs, Carries and Throws - Welding Victims Safely|Grabs, Carries and Throws - Welding Victims Safely]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
