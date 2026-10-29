---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Math Geometry/Community Knowledge/Frame-Rate Independent Smoothing - Exponential Decay and Springs.md"
---
# Frame-Rate Independent Smoothing - Exponential Decay and Springs — Development Guide

New practical guidance for [[03 Scripting and Systems/Math Geometry/Community Knowledge/Frame-Rate Independent Smoothing - Exponential Decay and Springs|Frame-Rate Independent Smoothing - Exponential Decay and Springs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The most common smoothing line in Roblox code is `x = x:Lerp(target, 0.1)` inside `RenderStepped`. It looks fine on the developer's PC and feels different everywhere else, because it closes 10% of the gap per frame. Players now run at 30, 60, 120 or 240 fps (Roblox has an FPS cap setting), so camera follow, UI counters, aim smoothing and pet following all change speed with frame rate. The fix is one formula; for...
**Useful source sections:** Why the naive lerp breaks, Fix 1: exponential decay with dt, Fix 2: critically damped spring.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Frame-Rate Independent Smoothing - Exponential Decay and Springs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Frame-Rate Independent Smoothing - Exponential Decay and Springs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Math Geometry/Community Knowledge/Frame-Rate Independent Smoothing - Exponential Decay and Springs|Frame-Rate Independent Smoothing - Exponential Decay and Springs]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
