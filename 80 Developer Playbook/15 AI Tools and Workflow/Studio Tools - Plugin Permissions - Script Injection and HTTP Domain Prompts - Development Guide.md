---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts.md"
---
# Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts|Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A plugin runs with more power than any game script. It can read every script in your place and change any instance. The two abilities that do the most damage, creating scripts and talking to the internet, are behind permission prompts. Knowing what the prompts mean, where to change your answer, and what a well-behaved plugin should ask for protects your game. If you write plugins, it also stops your users from...
**Useful source sections:** Why these permissions exist, HTTP permissions (per domain), Script Injection.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts|Studio Tools - Plugin Permissions - Script Injection and HTTP Domain Prompts]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
