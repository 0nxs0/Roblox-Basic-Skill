---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Free Animations/KeyframeSequence vs CurveAnimation - Export Paths.md"
---
# KeyframeSequence vs CurveAnimation - Export Paths — Development Guide

New practical guidance for [[40 Community Resources/Free Animations/KeyframeSequence vs CurveAnimation - Export Paths|KeyframeSequence vs CurveAnimation - Export Paths]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Object | Made by | Holds | Needed for ---|---|---|--- KeyframeSequence | Classic Animation Editor keyframes, Moon Animator export, DenS Blender add-on | Poses at keyframes + easing per pose | Normal gameplay animations CurveAnimation | Animation Editor's Curve Editor (converts on request), FBX imports | Per-channel float/rotation curves | Emotes (docs: emote data must be a CurveAnimation); smooth mocap with dense...
**Useful source sections:** The two local formats, Where local saves live, Paths to an ID.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For KeyframeSequence vs CurveAnimation - Export Paths, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using KeyframeSequence vs CurveAnimation - Export Paths and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Free Animations/KeyframeSequence vs CurveAnimation - Export Paths|KeyframeSequence vs CurveAnimation - Export Paths]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
