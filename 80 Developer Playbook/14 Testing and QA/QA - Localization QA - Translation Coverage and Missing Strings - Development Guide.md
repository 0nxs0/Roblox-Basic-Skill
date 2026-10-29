---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA - Localization QA - Translation Coverage and Missing Strings.md"
---
# QA - Localization QA - Translation Coverage and Missing Strings — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA - Localization QA - Translation Coverage and Missing Strings|QA - Localization QA - Translation Coverage and Missing Strings]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox can auto-translate a lot, but text built in scripts, numbers glued into sentences and images with words in them slip through. The visible result is a Spanish player seeing "Wave 3 begins!" in English beside a translated HUD. Pseudolocalization (covered in Player Emulator QA - Pseudolocalization, Text Elongation and Region) finds layout breaks; this note covers the other half: is every string actually...
**Useful source sections:** Where untranslated text comes from, Coverage check per release, In-game pass (per target language, 20 minutes).

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA - Localization QA - Translation Coverage and Missing Strings, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA - Localization QA - Translation Coverage and Missing Strings and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA - Localization QA - Translation Coverage and Missing Strings|QA - Localization QA - Translation Coverage and Missing Strings]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
