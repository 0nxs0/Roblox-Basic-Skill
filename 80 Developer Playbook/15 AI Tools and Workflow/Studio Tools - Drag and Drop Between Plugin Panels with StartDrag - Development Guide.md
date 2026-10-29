---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Drag and Drop Between Plugin Panels with StartDrag.md"
---
# Studio Tools - Drag and Drop Between Plugin Panels with StartDrag — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Drag and Drop Between Plugin Panels with StartDrag|Studio Tools - Drag and Drop Between Plugin Panels with StartDrag]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A prop palette where you drag a thumbnail feels far better than one where you click, then click again in the world. It is also the natural way to move items between two panels (for example from "kit library" to "this level's favourites"). Studio plugins get real OS-style drag and drop through `plugin:StartDrag()` and four events on every `PluginGui`. This note shows the data format and a palette-to-panel example,...
**Useful source sections:** Start a drag, Receive a drop in a PluginGui, Dropping into the 3D viewport.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Drag and Drop Between Plugin Panels with StartDrag, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Drag and Drop Between Plugin Panels with StartDrag and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Drag and Drop Between Plugin Panels with StartDrag|Studio Tools - Drag and Drop Between Plugin Panels with StartDrag]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
