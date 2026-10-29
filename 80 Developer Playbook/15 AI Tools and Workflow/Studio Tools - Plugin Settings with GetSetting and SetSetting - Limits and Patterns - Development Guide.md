---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns.md"
---
# Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns|Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A builder tool that forgets its grid size, its last-used prefab folder or its "don't show again" choice every time Studio restarts gets uninstalled. `plugin:SetSetting()` and `plugin:GetSetting()` give each plugin a small per-user, per-machine store that survives restarts. Used well, they make a plugin feel polished. Used badly, they corrupt their own file or lose data when two Studio windows are open.
**Useful source sections:** What the API is, Hard limits from the reference, Pattern: one versioned table, written rarely.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns|Studio Tools - Plugin Settings with GetSetting and SetSetting - Limits and Patterns]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
