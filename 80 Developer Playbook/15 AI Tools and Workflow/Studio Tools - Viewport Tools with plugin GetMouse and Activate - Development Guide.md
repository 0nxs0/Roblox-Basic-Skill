---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Viewport Tools with plugin GetMouse and Activate.md"
---
# Studio Tools - Viewport Tools with plugin GetMouse and Activate — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Viewport Tools with plugin GetMouse and Activate|Studio Tools - Viewport Tools with plugin GetMouse and Activate]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Click-to-place tools (scatter a tree where you click, paint decals onto walls, drop spawn points onto the floor) are the most satisfying plugins to use. They need control of the 3D viewport mouse. In Studio that means activating your plugin, which takes the mouse from the Move/Scale/Rotate tools, and reading clicks from a PluginMouse. This note covers the activation life cycle, accurate hit-testing and snapping...
**Useful source sections:** Activation rules, Hit-testing: prefer a raycast over mouse.Hit, Respect the user's snapping.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Viewport Tools with plugin GetMouse and Activate, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Viewport Tools with plugin GetMouse and Activate and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Viewport Tools with plugin GetMouse and Activate|Studio Tools - Viewport Tools with plugin GetMouse and Activate]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
