---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Lighting/Community Knowledge/Sky Instance - Custom Skyboxes, Sun, Moon and Stars.md"
---
# Sky Instance - Custom Skyboxes, Sun, Moon and Stars — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Lighting/Community Knowledge/Sky Instance - Custom Skyboxes, Sun, Moon and Stars|Sky Instance - Custom Skyboxes, Sun, Moon and Stars]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The sky fills a third to half of the screen in most outdoor games, so it sets the mood more than any single model. The `Sky` object (parented to `Lighting`) holds six cube-face images plus a procedural sun, moon and stars that move with the time of day. Getting the faces right, matching the sun to the painted sky, and using orientation and celestial settings well is a large visual upgrade for very little cost.
**Useful source sections:** The six faces, Celestial bodies, Orientation.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Sky Instance - Custom Skyboxes, Sun, Moon and Stars, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Sky Instance - Custom Skyboxes, Sun, Moon and Stars and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Lighting/Community Knowledge/Sky Instance - Custom Skyboxes, Sun, Moon and Stars|Sky Instance - Custom Skyboxes, Sun, Moon and Stars]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
