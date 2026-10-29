---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels.md"
---
# Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels|Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
When you press Play, Studio does not just run your game. It creates a separate server DataModel and one or more client DataModels next to the edit one. Plugins can be loaded into those too. A plugin that does not expect this ends up with duplicate toolbar buttons, a placement tool that edits the throw-away play copy, or an "auto-tag" script that runs three times. This note explains which copy of your plugin is...
**Useful source sections:** Which DataModels a plugin targets, The guard, What breaks in play mode.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels|Studio Tools - Plugins in Play Mode - Edit, Server and Client DataModels]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
