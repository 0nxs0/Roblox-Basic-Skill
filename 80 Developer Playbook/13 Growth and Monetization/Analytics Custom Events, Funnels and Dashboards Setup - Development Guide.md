---
kind: development-companion
category: "13 Growth and Monetization"
source-note: "13 Growth and Monetization/Analytics Discovery/Deep Dives/Analytics Custom Events, Funnels and Dashboards Setup.md"
---
# Analytics Custom Events, Funnels and Dashboards Setup — Development Guide

New practical guidance for [[13 Growth and Monetization/Analytics Discovery/Deep Dives/Analytics Custom Events, Funnels and Dashboards Setup|Analytics Custom Events, Funnels and Dashboards Setup]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`AnalyticsService:LogCustomEvent(player, eventName, value?, customFields?)` - Counter (no value) = value 1. Good for "button clicked", "quest started". - With value: durations, scores, counts. Also use it to batch ("10 zombies killed" once instead of 10 events), which keeps you under the rate limit. - Aggregations available on the Explore page: count, unique users, average, sum, min, max, average per user, all...
**Useful source sections:** Why this matters, 1. Ground rules (documented), 2. Custom events: what to track.

## Apply it
Use this topic as part of **improve discovery without misleading players**.
- **Define the contract:** For Analytics Custom Events, Funnels and Dashboards Setup, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** State the audience promise and first-session value; measure one funnel step before offers.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Show price and benefits clearly, respect platform rules, and avoid coercive timers.

## Validate before shipping
- **Expected path:** Build one small feature using Analytics Custom Events, Funnels and Dashboards Setup and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare conversion with satisfaction and test no-spend progression.

## Connected work
- Source note: [[13 Growth and Monetization/Analytics Discovery/Deep Dives/Analytics Custom Events, Funnels and Dashboards Setup|Analytics Custom Events, Funnels and Dashboards Setup]]
- Category hub: [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
