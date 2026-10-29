---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync.md"
---
# Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync|Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Studio's Union/Negate buttons are fine for one window hole. They don't scale to "cut a doorway in all 40 apartment walls" or "build a curved handrail that follows these 12 points". Scripted solid modeling does, from a plugin or the command bar. There are two API families: the old Plugin CSG methods that copy the toolbar buttons, and the newer GeometryService async methods with more options, including...
**Useful source sections:** Option A: Plugin methods (same as the toolbar), Option B: GeometryService (more control), Recipe: doorway in every selected wall.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync|Studio Tools - Scripted CSG for Builders - plugin Union, GeometryService and SweepPartAsync]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
