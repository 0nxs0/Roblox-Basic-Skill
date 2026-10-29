---
kind: development-companion
category: "07 AI and Combat"
source-note: "07 AI and Combat/AI/Community Knowledge/LLM NPC Dialogue with TextGenerator.md"
---
# LLM NPC Dialogue with TextGenerator — Development Guide

New practical guidance for [[07 AI and Combat/AI/Community Knowledge/LLM NPC Dialogue with TextGenerator|LLM NPC Dialogue with TextGenerator]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox's `TextGenerator` class gives game servers access to a hosted large language model, so NPCs can answer free-text questions in character. It launched as a beta around GDC 2025, and a later DevForum post expanded access to all experiences while adding a content-maturity rule: experiences with extended interactions with an AI NPC must carry a "Restricted" maturity rating (check the current guidelines before...
**Useful source sections:** The API in brief (from the reference), A server-side dialogue service, Design rules.

## Apply it
Use this topic as part of **make combat legible and fair**.
- **Define the contract:** For LLM NPC Dialogue with TextGenerator, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Separate perception, decision, action, and cooldown state; validate hits before polishing effects.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Test latency, repeated inputs, cancels, target switching, and attack cues.

## Validate before shipping
- **Expected path:** Build one small feature using LLM NPC Dialogue with TextGenerator and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Verify hitboxes, damage authority, cooldowns, and balance.

## Connected work
- Source note: [[07 AI and Combat/AI/Community Knowledge/LLM NPC Dialogue with TextGenerator|LLM NPC Dialogue with TextGenerator]]
- Category hub: [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/06 Characters and Animation/_Development Hub|06 Characters and Animation]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
