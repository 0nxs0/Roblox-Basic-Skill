---
kind: development-companion
category: "13 Growth and Monetization"
source-note: "13 Growth and Monetization/Publishing Release/Community Knowledge/Policy - PolicyService Compliance - Loot Boxes, Trading, Ads and Regions.md"
---
# PolicyService Compliance - Loot Boxes, Trading, Ads and Regions — Development Guide

New practical guidance for [[13 Growth and Monetization/Publishing Release/Community Knowledge/Policy - PolicyService Compliance - Loot Boxes, Trading, Ads and Regions|PolicyService Compliance - Loot Boxes, Trading, Ads and Regions]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`PolicyService:GetPolicyInfoForPlayerAsync(player)` is how Roblox tells your game what each player is legally allowed to do, based on location, age group and platform. The Community Standards list "skipping required PolicyService APIs" as misuse of Roblox systems, and the Help Center says you must integrate it to meet your compliance obligations. You never need to know why a player is restricted (Belgium, Brazil...
**Useful source sections:** The flags that matter most, Required treatments for restricted loot boxes, A server-side policy cache.

## Apply it
Use this topic as part of **improve discovery without misleading players**.
- **Define the contract:** For PolicyService Compliance - Loot Boxes, Trading, Ads and Regions, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** State the audience promise and first-session value; measure one funnel step before offers.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Show price and benefits clearly, respect platform rules, and avoid coercive timers.

## Validate before shipping
- **Expected path:** Build one small feature using PolicyService Compliance - Loot Boxes, Trading, Ads and Regions and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare conversion with satisfaction and test no-spend progression.

## Connected work
- Source note: [[13 Growth and Monetization/Publishing Release/Community Knowledge/Policy - PolicyService Compliance - Loot Boxes, Trading, Ads and Regions|PolicyService Compliance - Loot Boxes, Trading, Ads and Regions]]
- Category hub: [[80 Developer Playbook/13 Growth and Monetization/_Development Hub|13 Growth and Monetization development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
