---
kind: development-companion
category: "12 UI Audio and Camera"
source-note: "12 UI Audio and Camera/Audio/Community Knowledge/Voice Chat with the Audio API - Teams, Radios and Effects.md"
---
# Voice Chat with the Audio API - Teams, Radios and Effects — Development Guide

New practical guidance for [[12 UI Audio and Camera/Audio/Community Knowledge/Voice Chat with the Audio API - Teams, Radios and Effects|Voice Chat with the Audio API - Teams, Radios and Effects]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Voice chat is a strong retention feature for social, horror and squad games, and with `VoiceChatService.UseAudioApi` enabled, each player's microphone becomes an ordinary audio source you can route, filter and restrict. That enables team-only voice, walkie-talkies with static, monster voices, and megaphones, all without custom networking. It also carries responsibility: you decide who hears whom, so mistakes can...
**Useful source sections:** Who can use it, The default setup with UseAudioApi, AudioDeviceInput controls.

## Apply it
Use this topic as part of **communicate state across input modes**.
- **Define the contract:** For Voice Chat with the Audio API - Teams, Radios and Effects, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Map UI states to player actions and feedback; test safe areas, keyboard, gamepad, and touch early.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle focus, latency, respawn, captions, contrast, audio, and camera comfort.

## Validate before shipping
- **Expected path:** Build one small feature using Voice Chat with the Audio API - Teams, Radios and Effects and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test narrow screens, muted audio, controller navigation, and repeated input.

## Connected work
- Source note: [[12 UI Audio and Camera/Audio/Community Knowledge/Voice Chat with the Audio API - Teams, Radios and Effects|Voice Chat with the Audio API - Teams, Radios and Effects]]
- Category hub: [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera development hub]]
- Related disciplines: [[80 Developer Playbook/02 Game Design and Economy/_Development Hub|02 Game Design and Economy]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
