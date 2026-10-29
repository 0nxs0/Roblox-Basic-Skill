---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Performance - Fast Start-up and Light Background Work.md"
---
# Studio Tools - Plugin Performance - Fast Start-up and Light Background Work — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Performance - Fast Start-up and Light Background Work|Studio Tools - Plugin Performance - Fast Start-up and Light Background Work]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Every installed plugin runs when Studio opens each place, and copies can also load into playtest DataModels. Ten "small" plugins that each scan the whole Workspace at start-up, or listen to every property change, are why some people's Studio takes a minute to open and stutters while they drag parts. If you write plugins, keep them lazy and quiet. If you install them, these are the signs of a heavy one.
**Useful source sections:** Rule 1: do almost nothing at start-up, Rule 2: listen narrowly, Rule 3: chunk big jobs.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Plugin Performance - Fast Start-up and Light Background Work, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Plugin Performance - Fast Start-up and Light Background Work and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin Performance - Fast Start-up and Light Background Work|Studio Tools - Plugin Performance - Fast Start-up and Light Background Work]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
