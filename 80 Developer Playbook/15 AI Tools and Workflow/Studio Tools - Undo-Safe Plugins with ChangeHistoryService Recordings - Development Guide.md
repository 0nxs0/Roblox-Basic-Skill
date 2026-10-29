---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings.md"
---
# Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings|Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
A plugin that changes the place without telling the undo system is dangerous: the builder presses `Ctrl+Z` and either nothing happens or an unrelated earlier action is undone. Every plugin, command-bar macro or AI tool that edits the DataModel should wrap each user action in a ChangeHistoryService recording. Then one click is one undo step, with a readable name in the Edit menu.
**Useful source sections:** The modern API (use this), A safe wrapper, Rules from the reference.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings|Studio Tools - Undo-Safe Plugins with ChangeHistoryService Recordings]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
