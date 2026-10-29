---
kind: development-companion
category: "00 Inbox"
source-note: "00 Inbox/Inbox.md"
---
# Inbox — Development Guide

New practical guidance for [[00 Inbox/Inbox|Inbox]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
New notes land here. Move each one into its colour area when you know where it belongs.

## Apply it
Use this topic as part of **scope ideas into shippable tasks**.
- **Define the contract:** For Inbox, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** State the player outcome, owner, acceptance check, and next step before implementation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Mark assumptions instead of turning guesses into requirements.

## Validate before shipping
- **Expected path:** Build one small feature using Inbox and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can another developer tell when the task is done?

## Connected work
- Source note: [[00 Inbox/Inbox|Inbox]]
- Category hub: [[80 Developer Playbook/00 Inbox/_Development Hub|00 Inbox development hub]]
