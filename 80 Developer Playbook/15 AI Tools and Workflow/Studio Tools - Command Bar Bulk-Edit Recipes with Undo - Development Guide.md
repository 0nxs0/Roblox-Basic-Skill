---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Command Bar Bulk-Edit Recipes with Undo.md"
---
# Studio Tools - Command Bar Bulk-Edit Recipes with Undo — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Command Bar Bulk-Edit Recipes with Undo|Studio Tools - Command Bar Bulk-Edit Recipes with Undo]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The command bar (View > Command Bar) runs Luau in the edit DataModel with plugin-level access, right now, with no plugin to install. It is the builder's power tool for one-off jobs too fiddly for the Properties window: numbered renames, random rotations, dropping props to the ground, swapping placeholders for real models. The multi-line command bar records its changes with ChangeHistoryService, so a run can...
**Useful source sections:** Ground rules, 1. Numbered rename (Lamp01, Lamp02...), 2. Random Y rotation (rocks, trees, crates).

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Command Bar Bulk-Edit Recipes with Undo, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Command Bar Bulk-Edit Recipes with Undo and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Command Bar Bulk-Edit Recipes with Undo|Studio Tools - Command Bar Bulk-Edit Recipes with Undo]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
