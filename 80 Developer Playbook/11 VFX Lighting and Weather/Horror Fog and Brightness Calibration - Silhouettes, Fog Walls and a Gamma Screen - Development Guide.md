---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen.md"
---
# Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen|Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Horror games live on the line between "I can't see what's out there" (scary) and "I can't see anything" (players quit). The vault already covers horror lighting values and readable darkness; this note covers the two tools that most decide which side you land on: what colour and density your fog is, and whether each player's screen is calibrated. Roblox players use everything from dim phones to bright TVs, so a...
**Useful source sections:** Dark fog vs light fog, Atmosphere knobs (from the docs), Fake flashlight beams in fog.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Lighting/Community Knowledge/FX - Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen|Horror Fog and Brightness Calibration - Silhouettes, Fog Walls and a Gamma Screen]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
