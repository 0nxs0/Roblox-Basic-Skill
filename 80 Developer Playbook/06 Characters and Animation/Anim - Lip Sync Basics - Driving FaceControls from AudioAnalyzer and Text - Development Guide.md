---
kind: development-companion
category: "06 Characters and Animation"
source-note: "06 Characters and Animation/Animation/Community Knowledge/Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text.md"
---
# Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text — Development Guide

New practical guidance for [[06 Characters and Animation/Animation/Community Knowledge/Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text|Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
An NPC that talks with a frozen mouth looks like a statue with a speaker inside. Full phoneme lip sync is hard, but "jaw flap" lip sync (mouth opens with loudness, closes on silence, with a little shape variety) is cheap on Roblox and good enough at gameplay distance. You need a dynamic head (a head `MeshPart` with a `FaceControls` child) and either voiced audio or text.
**Useful source sections:** Facts that shape the design, Method 1: loudness-driven jaw (voiced lines), Method 2: text-driven flap (no audio, or TTS).

## Apply it
Use this topic as part of **make character motion readable**.
- **Define the contract:** For Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Name movement states and transition rules; tune one transition at a time against the rig and camera.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Handle interruption, respawn, tool use, replication, and animation priority.

## Validate before shipping
- **Expected path:** Build one small feature using Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test slopes, jumps, interruptions, and multiple observers.

## Connected work
- Source note: [[06 Characters and Animation/Animation/Community Knowledge/Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text|Anim - Lip Sync Basics - Driving FaceControls from AudioAnalyzer and Text]]
- Category hub: [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation development hub]]
- Related disciplines: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/08 Vehicles/_Development Hub|08 Vehicles]], [[80 Developer Playbook/12 UI Audio and Camera/_Development Hub|12 UI Audio and Camera]]
