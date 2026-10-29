---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop.md"
---
# Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop|Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Small builder plugins are a near-perfect job for an AI coding assistant. They are short, use a well-documented API, and are easy to test by eye. They are also plugins, so a careless one can rewrite scripts, break undo, or phone home. This note is a repeatable loop for getting a good plugin out of Claude (or any assistant): a spec that names the right APIs, a review checklist that catches the usual AI mistakes,...
**Useful source sections:** 1. Write the spec (paste this, fill in the blanks), 2. Review checklist (5 minutes, every time), 3. Test routine.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop|Studio Tools - Having an AI Write Your Studio Plugin - Spec, Review and Test Loop]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
