---
kind: development-companion
category: "13 Growth and Monetization"
source-note: "13 Growth and Monetization/Analytics Discovery/Deep Dives/Experiments and Configs - In-Game A-B Testing.md"
---
# Experiments and Configs - In-Game A-B Testing — Development Guide

New practical guidance for [[13 Growth and Monetization/Analytics Discovery/Deep Dives/Experiments and Configs - In-Game A-B Testing|Experiments and Configs - In-Game A-B Testing]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Code rules: - `ConfigService` is server-only; client calls error. - `ConfigService:GetConfigAsync()` gives a global snapshot (no targeting, no experiments). - `ConfigService:GetConfigForPlayerAsync(player)` gives a per-player snapshot (targeting and experiments). - Snapshots are point-in-time. Updates don't apply until you call `snapshot:Refresh()`. Listen to `UpdateAvailable`, then `GetValueChangedSignal(key)`....
**Useful source sections:** Why this matters, 1. Configs: live values without a publish, 2. Experiments: real A/B tests.

## Apply it
Use this topic as part of **improve discovery without misleading players**.
- **Define the contract:** For Experiments and Configs - In-Game A-B Testing, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** State the audience promise and first-session value; measure one funnel step before offers.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Show price and benefits clearly, respect platform rules, and avoid coercive timers.

## Validate before shipping
- **Expected path:** Build one small feature using Experiments and Configs - In-Game A-B Testing and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare conversion with satisfaction and test no-spend progression.

## Connected work
- Source note: [[13 Growth and Monetization/Analytics Discovery/Deep Dives/Experiments and Configs - In-Game A-B Testing|Experiments and Configs - In-Game A-B Testing]]
- Category hub: [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
