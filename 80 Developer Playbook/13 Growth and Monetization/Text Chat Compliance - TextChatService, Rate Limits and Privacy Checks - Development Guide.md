---
kind: development-companion
category: "13 Growth and Monetization"
source-note: "13 Growth and Monetization/Publishing Release/Community Knowledge/Policy - Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks.md"
---
# Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks — Development Guide

New practical guidance for [[13 Growth and Monetization/Publishing Release/Community Knowledge/Policy - Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks|Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Player-to-player text is a platform rule, not a design choice: if users can message each other in your game, the messages must go through `TextChatService`. Custom chat that bypasses it is listed under "Misusing Roblox Systems" in the Community Standards. The legacy `Chat` service was removed on the schedule below, so old free-model chat systems are now a compliance risk as well as a bug risk.
**Useful source sections:** What counts as chat, The requirements, Migration timeline (from the announcement).

## Apply it
Use this topic as part of **improve discovery without misleading players**.
- **Define the contract:** For Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** State the audience promise and first-session value; measure one funnel step before offers.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Show price and benefits clearly, respect platform rules, and avoid coercive timers.

## Validate before shipping
- **Expected path:** Build one small feature using Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare conversion with satisfaction and test no-spend progression.

## Connected work
- Source note: [[13 Growth and Monetization/Publishing Release/Community Knowledge/Policy - Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks|Text Chat Compliance - TextChatService, Rate Limits and Privacy Checks]]
- Category hub: [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
