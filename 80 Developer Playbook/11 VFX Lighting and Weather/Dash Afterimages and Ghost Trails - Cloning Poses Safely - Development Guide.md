---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Dash Afterimages and Ghost Trails - Cloning Poses Safely.md"
---
# Dash Afterimages and Ghost Trails - Cloning Poses Safely — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Dash Afterimages and Ghost Trails - Cloning Poses Safely|Dash Afterimages and Ghost Trails - Cloning Poses Safely]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Afterimages (fading copies of the character left along a dash path) make a dodge or teleport-dash readable and feel fast. The DevForum threads in the sources show the usual first attempts and their bugs: cloning body parts that still carry welds anchors the real player, afterimages stop after death because the script held the old character, and server-made clones look wrong for the dasher while client-made ones...
**Useful source sections:** Rule 1: build afterimages on every client, never the server, Rule 2: snapshot parts, not the character, Rule 3: sample on a timer, not every frame.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Dash Afterimages and Ghost Trails - Cloning Poses Safely, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Dash Afterimages and Ghost Trails - Cloning Poses Safely and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/VFX/Community Knowledge/FX - Dash Afterimages and Ghost Trails - Cloning Poses Safely|Dash Afterimages and Ghost Trails - Cloning Poses Safely]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
