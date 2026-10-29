---
kind: development-companion
category: "13 Growth and Monetization"
source-note: "13 Growth and Monetization/LiveOps Social/Deep Dives/Invites, Referrals, Share Links and Notifications.md"
---
# Invites, Referrals, Share Links and Notifications — Development Guide

New practical guidance for [[13 Growth and Monetization/LiveOps Social/Deep Dives/Invites, Referrals, Share Links and Notifications|Invites, Referrals, Share Links and Notifications]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
All launch data is read on the server with `player:GetJoinData()`. Treat it as untrusted input: anyone can craft a link.
**Useful source sections:** Why this matters, 1. Tool overview, 2. Invite prompts.

## Apply it
Use this topic as part of **improve discovery without misleading players**.
- **Define the contract:** For Invites, Referrals, Share Links and Notifications, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** State the audience promise and first-session value; measure one funnel step before offers.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Show price and benefits clearly, respect platform rules, and avoid coercive timers.

## Validate before shipping
- **Expected path:** Build one small feature using Invites, Referrals, Share Links and Notifications and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare conversion with satisfaction and test no-spend progression.

## Connected work
- Source note: [[13 Growth and Monetization/LiveOps Social/Deep Dives/Invites, Referrals, Share Links and Notifications|Invites, Referrals, Share Links and Notifications]]
- Category hub: [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
