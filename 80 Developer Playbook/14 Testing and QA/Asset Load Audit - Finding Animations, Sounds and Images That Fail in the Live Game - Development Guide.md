---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/Test - Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game.md"
---
# Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/Test - Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game|Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"The animation plays for me but not for players" is one of the most common Roblox bug reports, and it is almost always ownership or permission, not code: the animation was published under a personal account while the game belongs to a group, a sound was uploaded by a collaborator, or an image is Restricted and was never granted to this game. These bugs hide in Studio because you may have access, and they appear...
**Useful source sections:** Why assets fail, The audit script, Also listen during normal playtests.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/Test - Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game|Asset Load Audit - Finding Animations, Sounds and Images That Fail in the Live Game]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
