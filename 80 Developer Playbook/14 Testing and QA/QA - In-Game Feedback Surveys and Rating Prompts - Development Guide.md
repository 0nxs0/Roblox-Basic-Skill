---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA - In-Game Feedback Surveys and Rating Prompts.md"
---
# QA - In-Game Feedback Surveys and Rating Prompts — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA - In-Game Feedback Surveys and Rating Prompts|QA - In-Game Feedback Surveys and Rating Prompts]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Discord feedback comes from your biggest fans; most players never join. A small in-game survey reaches the silent majority at the exact moment they have an opinion (end of a round, after the tutorial, after leaving the shop without buying). Roblox's beta-testing guide recommends in-game feedback for exactly this, and warns that leading questions and poor survey design make the data useless.
**Useful source sections:** What Roblox already gives you, Design the survey, Free text: be careful.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA - In-Game Feedback Surveys and Rating Prompts, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA - In-Game Feedback Surveys and Rating Prompts and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA - In-Game Feedback Surveys and Rating Prompts|QA - In-Game Feedback Surveys and Rating Prompts]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
