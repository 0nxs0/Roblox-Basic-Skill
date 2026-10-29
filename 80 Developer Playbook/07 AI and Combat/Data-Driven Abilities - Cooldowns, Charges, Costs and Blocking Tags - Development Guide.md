---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/Combat/Community Knowledge/Fight - Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags.md"
---
# Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags — Development Guide

New practical guidance for [[07 AI and Combat/Combat/Community Knowledge/Fight - Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags|Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A battlegrounds or MOBA-style game ships 40+ abilities. If each one is a hand-written script with its own `debounce` and `wait(5)`, you get exploitable cooldowns, abilities that can be cast while stunned, and no way to balance them in one place. Unreal's Gameplay Ability System (documented by the community in tranek's GASDocumentation, MIT) shows a cleaner split that ports well to Luau: abilities are data,...
**Useful source sections:** 1. One definition per ability, 2. Cooldowns are timestamps, not waits, 3. Charges (ammo-style abilities).

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/Combat/Community Knowledge/Fight - Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags|Data-Driven Abilities - Cooldowns, Charges, Costs and Blocking Tags]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
