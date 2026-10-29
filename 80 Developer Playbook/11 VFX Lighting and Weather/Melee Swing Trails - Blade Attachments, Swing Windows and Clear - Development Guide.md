---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Melee Swing Trails - Blade Attachments, Swing Windows and Clear.md"
---
# Melee Swing Trails - Blade Attachments, Swing Windows and Clear — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Melee Swing Trails - Blade Attachments, Swing Windows and Clear|Melee Swing Trails - Blade Attachments, Swing Windows and Clear]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A sword, bat or axe trail is the single cheapest thing that makes melee feel powerful: one `Trail` instance per weapon, a few properties, and a toggle at the right animation frames. The vault's Beams and Trails deep dive lists the Trail properties; this note is the melee-specific recipe and the bugs people hit: streaks across the map after a teleport, trails that keep drawing when an attack is cancelled, and...
**Useful source sections:** Rig: base and tip attachments, Settings that read well, Enable only during the swing window.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Melee Swing Trails - Blade Attachments, Swing Windows and Clear, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Melee Swing Trails - Blade Attachments, Swing Windows and Clear and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Melee Swing Trails - Blade Attachments, Swing Windows and Clear|Melee Swing Trails - Blade Attachments, Swing Windows and Clear]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
