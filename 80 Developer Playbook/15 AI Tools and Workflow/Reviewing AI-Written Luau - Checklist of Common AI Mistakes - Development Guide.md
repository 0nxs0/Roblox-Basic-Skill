---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Reviewing AI-Written Luau - Checklist of Common AI Mistakes.md"
---
# Reviewing AI-Written Luau - Checklist of Common AI Mistakes — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Reviewing AI-Written Luau - Checklist of Common AI Mistakes|Reviewing AI-Written Luau - Checklist of Common AI Mistakes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The existing AI Code Review Prompt lists what areas to review. This note lists the specific mistakes AI models make again and again in Roblox code, so a human (or a second AI pass) can scan for them in minutes. The pattern behind most of them: models learned from years of old tutorials and free models, so they reproduce outdated APIs and the trust mistakes those tutorials made. Roblox's own docs for Code Assist...
**Useful source sections:** A. Outdated or deprecated APIs (search the diff for these strings), B. Trust and security mistakes, C. Data and lifecycle mistakes.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Reviewing AI-Written Luau - Checklist of Common AI Mistakes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Reviewing AI-Written Luau - Checklist of Common AI Mistakes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Reviewing AI-Written Luau - Checklist of Common AI Mistakes|Reviewing AI-Written Luau - Checklist of Common AI Mistakes]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
