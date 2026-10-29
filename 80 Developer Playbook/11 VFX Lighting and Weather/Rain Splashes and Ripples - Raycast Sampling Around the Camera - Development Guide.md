---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Weather/Community Knowledge/Rain Splashes and Ripples - Raycast Sampling Around the Camera.md"
---
# Rain Splashes and Ripples - Raycast Sampling Around the Camera — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Weather/Community Knowledge/Rain Splashes and Ripples - Raycast Sampling Around the Camera|Rain Splashes and Ripples - Raycast Sampling Around the Camera]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Falling rain alone looks like a screen filter. What makes it feel like rain is the ground reacting: small splashes on pavement, rings on puddles and water, drips off roofs, and no splashes under cover. You can't simulate every drop, but you can fake impacts by raycasting a few random points around the camera each frame and playing a tiny splash where they land. Players only notice splashes close to them, so 20-60...
**Useful source sections:** How it works, Code sketch (client), Effect settings.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Rain Splashes and Ripples - Raycast Sampling Around the Camera, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Rain Splashes and Ripples - Raycast Sampling Around the Camera and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Weather/Community Knowledge/Rain Splashes and Ripples - Raycast Sampling Around the Camera|Rain Splashes and Ripples - Raycast Sampling Around the Camera]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
