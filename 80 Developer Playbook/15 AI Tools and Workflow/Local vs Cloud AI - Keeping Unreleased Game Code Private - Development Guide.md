---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Local vs Cloud AI - Keeping Unreleased Game Code Private.md"
---
# Local vs Cloud AI - Keeping Unreleased Game Code Private — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Local vs Cloud AI - Keeping Unreleased Game Code Private|Local vs Cloud AI - Keeping Unreleased Game Code Private]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Your unreleased game is your competitive edge: a new mechanic, an economy design, an anti-cheat trick. Every AI tool you paste it into has a data policy, and those policies differ by product, plan and setting. You do not need to be paranoid, but you should decide on purpose which tool sees what. This note gives a simple tiering plan and the settings to check.
**Useful source sections:** What actually happens to pasted code, Roblox's own data-sharing switch, A tiering plan for a small studio.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Local vs Cloud AI - Keeping Unreleased Game Code Private, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Local vs Cloud AI - Keeping Unreleased Game Code Private and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Local vs Cloud AI - Keeping Unreleased Game Code Private|Local vs Cloud AI - Keeping Unreleased Game Code Private]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
