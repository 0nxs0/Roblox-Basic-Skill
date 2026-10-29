---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/UIDragDetector Sliders and Drag-and-Drop Inventory.md"
---
# UIDragDetector Sliders and Drag-and-Drop Inventory — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/UIDragDetector Sliders and Drag-and-Drop Inventory|UIDragDetector Sliders and Drag-and-Drop Inventory]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Volume sliders, sensitivity bars, colour pickers and drag-to-equip inventories used to need hand-written mouse and touch code (InputBegan, InputChanged, touch IDs, screen inset maths). A `UIDragDetector` placed under any `GuiObject` makes it draggable with mouse, touch and gamepad selection, and fires events your scripts can use. This note covers the two jobs people build most: a settings slider and an inventory...
**Useful source sections:** Key properties, Recipe 1: settings slider (0 to 1), Recipe 2: inventory drag-and-drop.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For UIDragDetector Sliders and Drag-and-Drop Inventory, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using UIDragDetector Sliders and Drag-and-Drop Inventory and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/UIDragDetector Sliders and Drag-and-Drop Inventory|UIDragDetector Sliders and Drag-and-Drop Inventory]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
