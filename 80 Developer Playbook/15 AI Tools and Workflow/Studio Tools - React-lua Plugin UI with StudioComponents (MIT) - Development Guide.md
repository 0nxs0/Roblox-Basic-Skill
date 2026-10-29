---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - React-lua Plugin UI with StudioComponents (MIT).md"
---
# Studio Tools - React-lua Plugin UI with StudioComponents (MIT) — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - React-lua Plugin UI with StudioComponents (MIT)|Studio Tools - React-lua Plugin UI with StudioComponents (MIT)]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Hand-building checkboxes, dropdowns and colour pickers for a plugin panel takes days, and they never quite match Studio. StudioComponents by sircfenner is a set of react-lua components that copy the look of Studio's own controls and follow the Studio theme for you. If your team already writes UI with React-lua (see UI Libraries - Fusion, React-lua, Vide and Iris), this is the fastest way to a plugin that looks...
**Useful source sections:** Facts (checked 2026-10-25), What it exports, How to wire it up.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - React-lua Plugin UI with StudioComponents (MIT), write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - React-lua Plugin UI with StudioComponents (MIT) and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - React-lua Plugin UI with StudioComponents (MIT)|Studio Tools - React-lua Plugin UI with StudioComponents (MIT)]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
