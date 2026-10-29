---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/9-Slice Panels and Buttons - SliceCenter and SliceScale.md"
---
# 9-Slice Panels and Buttons - SliceCenter and SliceScale — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/9-Slice Panels and Buttons - SliceCenter and SliceScale|9-Slice Panels and Buttons - SliceCenter and SliceScale]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most stylised game UI (wooden signs, sci-fi frames, pixel-art boxes, speech bubbles) is built from a handful of border images. If you stretch those images, the corners smear and the border gets thick on wide buttons. 9-slicing splits one image into a 3x3 grid: corners never scale, edges stretch along one axis, and only the centre stretches both ways. One small texture then fits every button, tooltip and dialog...
**Useful source sections:** How the grid scales, Setup in Studio, SliceScale: one texture, many border thicknesses.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For 9-Slice Panels and Buttons - SliceCenter and SliceScale, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using 9-Slice Panels and Buttons - SliceCenter and SliceScale and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/9-Slice Panels and Buttons - SliceCenter and SliceScale|9-Slice Panels and Buttons - SliceCenter and SliceScale]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
