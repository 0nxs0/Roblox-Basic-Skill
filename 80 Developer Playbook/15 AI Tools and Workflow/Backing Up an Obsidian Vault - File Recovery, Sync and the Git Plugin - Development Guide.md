---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Obsidian Workflow/Community Knowledge/Flow - Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin.md"
---
# Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Obsidian Workflow/Community Knowledge/Flow - Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin|Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A game design vault slowly becomes the only copy of your design decisions, balance notes, asset licences and resume notes for AI agents. Losing it hurts more than losing a week of code, because code is in Git and the reasons behind it are not. Obsidian vaults are plain folders of Markdown, so backing them up is easy, but the built-in safety net is not a backup. This note sorts the options.
**Useful source sections:** Layer 1: File recovery (core plugin) is an undo, not a backup, Layer 2: Sync (devices) is also not a backup, Layer 3: Git, a real history.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Obsidian Workflow/Community Knowledge/Flow - Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin|Backing Up an Obsidian Vault - File Recovery, Sync and the Git Plugin]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
