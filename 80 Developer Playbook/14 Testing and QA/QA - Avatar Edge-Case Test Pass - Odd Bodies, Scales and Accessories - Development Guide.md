---
kind: development-companion
category: "14 Testing and QA"
source-note: "14 Testing and QA/Testing/Community Knowledge/QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories.md"
---
# QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories — Development Guide

New practical guidance for [[14 Testing and QA/Testing/Community Knowledge/QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories|QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Your dev team tests with its own avatars, which are usually normal-sized R15 bodies. Real players arrive as tiny proportions, very tall bodies, huge layered coats, animation packs, wide wings, and heads with no face. Hitboxes, doors, seats, cameras and first-person views then break in ways no one on the team ever saw. A 20-minute avatar pass with a fixed set of test outfits catches this before players post the clip.
**Useful source sections:** Build a test outfit set, Test steps per outfit (about 3 minutes each), Decide what you enforce.

## Apply it
Use this topic as part of **make bugs reproducible and releases evidence-based**.
- **Define the contract:** For QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record setup, actions, expected and actual results, and first known bad build.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Cover platform, network, save, lifecycle, and load; keep private data out of logs.

## Validate before shipping
- **Expected path:** Build one small feature using QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Re-run regressions after fixes and attach evidence.

## Connected work
- Source note: [[14 Testing and QA/Testing/Community Knowledge/QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories|QA - Avatar Edge-Case Test Pass - Odd Bodies, Scales and Accessories]]
- Category hub: [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]]
