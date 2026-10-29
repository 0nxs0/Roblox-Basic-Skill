---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/UI UX/Community Knowledge/Rich Text and Typewriter Dialogue - MaxVisibleGraphemes.md"
---
# Rich Text and Typewriter Dialogue - MaxVisibleGraphemes — Development Guide

New practical guidance for [[12 UI Audio and Camera/UI UX/Community Knowledge/Rich Text and Typewriter Dialogue - MaxVisibleGraphemes|Rich Text and Typewriter Dialogue - MaxVisibleGraphemes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
NPC dialogue, quest text, item descriptions and kill feeds all want inline styling: a coloured item name, a bold number, a highlighted keyword. Rich text lets one `TextLabel` do that without stacking several labels. Combined with `MaxVisibleGraphemes`, it also gives you the classic typewriter reveal with no layout jumping.
**Useful source sections:** Turn it on, Tags worth knowing, Keep colours in one place.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Rich Text and Typewriter Dialogue - MaxVisibleGraphemes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Rich Text and Typewriter Dialogue - MaxVisibleGraphemes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/UI UX/Community Knowledge/Rich Text and Typewriter Dialogue - MaxVisibleGraphemes|Rich Text and Typewriter Dialogue - MaxVisibleGraphemes]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
