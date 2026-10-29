---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload.md"
---
# Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload|Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A Studio plugin is just a Script that runs inside Studio with extra permissions (`PluginSecurity`), plus a global called `plugin`. Once you can write one, every repetitive building chore (rename 200 parts, snap lamps to a wall, add a tag to a selection) becomes one button. This note gets you from nothing to a working toolbar button with a fast edit-reload loop. The rest of the "Studio Tools" notes build on it.
**Useful source sections:** Step 0: turn on plugin debugging, Step 1: write the script, Step 2: save it as a local plugin.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload|Studio Tools - Your First Plugin - Toolbar Button, PluginDebugService and Save and Reload]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
