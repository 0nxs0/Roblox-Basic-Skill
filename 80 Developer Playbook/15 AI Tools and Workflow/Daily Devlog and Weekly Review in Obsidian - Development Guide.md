---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Obsidian Workflow/Community Knowledge/Flow - Daily Devlog and Weekly Review in Obsidian.md"
---
# Daily Devlog and Weekly Review in Obsidian — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Obsidian Workflow/Community Knowledge/Flow - Daily Devlog and Weekly Review in Obsidian|Daily Devlog and Weekly Review in Obsidian]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A two-minute daily devlog is the cheapest productivity tool a Roblox dev can have. It answers "what did I do last Tuesday?", gives an AI assistant instant context when you resume, feeds your public update logs and devlog videos, and makes the weekly review honest. Obsidian's core Daily notes plugin plus one template is all you need.
**Useful source sections:** Setup (core plugins only), The daily template, Did.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Daily Devlog and Weekly Review in Obsidian, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Daily Devlog and Weekly Review in Obsidian and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Obsidian Workflow/Community Knowledge/Flow - Daily Devlog and Weekly Review in Obsidian|Daily Devlog and Weekly Review in Obsidian]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
