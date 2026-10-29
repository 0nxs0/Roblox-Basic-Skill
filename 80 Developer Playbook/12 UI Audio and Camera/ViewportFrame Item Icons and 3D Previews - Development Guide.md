---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/ViewportFrame Item Icons and 3D Previews.md"
---
# ViewportFrame Item Icons and 3D Previews — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/ViewportFrame Item Icons and 3D Previews|ViewportFrame Item Icons and 3D Previews]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Shops and inventories look far better when items show as real 3D models: a spinning sword on the buy screen, a car turntable in the garage, live weapon skins. A `ViewportFrame` renders 3D objects through its own `Camera` into a 2D frame. It is also easy to overuse: every viewport is another render, so a 60-slot grid of live viewports is a common cause of UI lag. This note covers framing an item automatically and...
**Useful source sections:** Minimal setup, Auto-framing any model, Spinning preview without moving the model.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For ViewportFrame Item Icons and 3D Previews, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using ViewportFrame Item Icons and 3D Previews and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/ViewportFrame Item Icons and 3D Previews|ViewportFrame Item Icons and 3D Previews]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
