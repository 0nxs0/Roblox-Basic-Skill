---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Audio/Community Knowledge/AudioAnalyzer - Visualizers and Loudness-Driven Effects.md"
---
# AudioAnalyzer - Visualizers and Loudness-Driven Effects — Development Guide

New practical guidance for [[12 UI Audio and Camera/Audio/Community Knowledge/AudioAnalyzer - Visualizers and Loudness-Driven Effects|AudioAnalyzer - Visualizers and Loudness-Driven Effects]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Club and concert games, rhythm minigames, "speaker bass shakes the room" moments, and lights that pulse with the music all need to know how loud the audio is right now. The legacy `Sound.PlaybackLoudness` gave one number. In the new Audio API, an `AudioAnalyzer` wired into any stream gives peak and RMS level and an optional frequency spectrum, so bass and treble can drive different effects.
**Useful source sections:** What the analyzer gives you, Wiring, Turning numbers into motion.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For AudioAnalyzer - Visualizers and Loudness-Driven Effects, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using AudioAnalyzer - Visualizers and Loudness-Driven Effects and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Audio/Community Knowledge/AudioAnalyzer - Visualizers and Loudness-Driven Effects|AudioAnalyzer - Visualizers and Loudness-Driven Effects]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
