---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Custom Gizmos with Handles and ArcHandles.md"
---
# Studio Tools - Custom Gizmos with Handles and ArcHandles — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Custom Gizmos with Handles and ArcHandles|Studio Tools - Custom Gizmos with Handles and ArcHandles]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Studio's Move/Scale/Rotate draggers are great for parts. They can't edit things that aren't parts: a spawn zone's radius stored as an attribute, a camera rail's control point, a light's range, a door's swing angle. Handles (arrows or spheres along the faces) and ArcHandles (rotation rings) let a plugin draw its own drag gizmos in the viewport and turn mouse drags into any value you like. That gives designers...
**Useful source sections:** The two classes, Example: drag a zone radius stored as an attribute, Rotation with ArcHandles.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Custom Gizmos with Handles and ArcHandles, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Custom Gizmos with Handles and ArcHandles and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Custom Gizmos with Handles and ArcHandles|Studio Tools - Custom Gizmos with Handles and ArcHandles]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
