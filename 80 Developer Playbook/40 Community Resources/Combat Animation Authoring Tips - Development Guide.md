---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Free Animations/Combat Animation Authoring Tips.md"
---
# Combat Animation Authoring Tips — Development Guide

New practical guidance for [[40 Community Resources/Free Animations/Combat Animation Authoring Tips|Combat Animation Authoring Tips]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Phase | Light attack | Heavy attack | What sells it ---|---|---|--- Anticipation (wind-up) | 3-5 frames | 8-14 frames | Pull the weapon back, shift weight to the back foot, tense the shoulders. Too subtle = weak; too long = sluggish Impact (active) | 2-3 frames | 3-4 frames | Fastest part of the clip; big arc, torso twist, front foot plants. Hold the contact pose 1-2 frames (or use hitstop in code) Recovery |...
**Useful source sections:** The three phases, in frames at 30 fps, Authoring rules for Roblox, Marker-driven windows (original Luau).

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For Combat Animation Authoring Tips, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using Combat Animation Authoring Tips and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Free Animations/Combat Animation Authoring Tips|Combat Animation Authoring Tips]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
