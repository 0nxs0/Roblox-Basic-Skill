---
kind: development-companion
category: "11 VFX Lighting and Weather"
source-note: "11 VFX Lighting and Weather/Lighting/Community Knowledge/Local Light Budgets - PointLight, SpotLight and SurfaceLight.md"
---
# Local Light Budgets - PointLight, SpotLight and SurfaceLight — Development Guide

New practical guidance for [[11 VFX Lighting and Weather/Lighting/Community Knowledge/Local Light Budgets - PointLight, SpotLight and SurfaceLight|Local Light Budgets - PointLight, SpotLight and SurfaceLight]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Local lights are what make a night street, a neon arcade or a torch-lit dungeon look rich, and they are also one of the easiest ways to tank frame rate, mostly because of shadows. Roblox's performance guide lists "excessive shadow casting" from many dense shadow-casting lights as a common render problem. This note is a practical budget: which light to use, how far it should reach, and which ones get shadows.
**Useful source sections:** Pick the right light, The budget (starting rules), Fake it where you can.

## Apply it
Use this topic as part of **keep effects readable and affordable**.
- **Define the contract:** For Local Light Budgets - PointLight, SpotLight and SurfaceLight, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Prototype timing, color, and silhouette against the real camera with an effect budget.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Pool repeated effects, cap lifetimes, preserve hazard readability, and test mobile.

## Validate before shipping
- **Expected path:** Build one small feature using Local Light Budgets - PointLight, SpotLight and SurfaceLight and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check cleanup, simultaneous effects, and frame cost.

## Connected work
- Source note: [[11 VFX Lighting and Weather/Lighting/Community Knowledge/Local Light Budgets - PointLight, SpotLight and SurfaceLight|Local Light Budgets - PointLight, SpotLight and SurfaceLight]]
- Category hub: [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
