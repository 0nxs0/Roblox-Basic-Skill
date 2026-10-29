---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/UIStroke, UIGradient and UIShadow Recipes.md"
---
# UIStroke, UIGradient and UIShadow Recipes — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/UIStroke, UIGradient and UIShadow Recipes|UIStroke, UIGradient and UIShadow Recipes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Appearance modifiers are child objects that change how their parent draws. They replace most of the old "stack three ImageLabels for an outline and a shadow" tricks, need no uploaded images, and scale cleanly on every screen. This note lists the properties that matter and recipes for outlined text, shiny buttons, rarity glows and soft shadows. Some features below were marked Beta (File > Beta Features) in the...
**Useful source sections:** UIStroke, UIGradient, UIShadow (beta at time of writing).

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For UIStroke, UIGradient and UIShadow Recipes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using UIStroke, UIGradient and UIShadow Recipes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/UIStroke, UIGradient and UIShadow Recipes|UIStroke, UIGradient and UIShadow Recipes]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
