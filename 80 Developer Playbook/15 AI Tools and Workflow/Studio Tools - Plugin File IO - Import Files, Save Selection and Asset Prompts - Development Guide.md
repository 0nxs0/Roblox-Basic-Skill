---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts.md"
---
# Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts|Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Plugins can't read your hard drive freely. That is good for security, but it means people often assume plugins can't import data at all. They can, through user-approved file dialogs: the user picks a file, and your plugin gets its bytes. That is enough for real build tools: placing props from a CSV exported by a level-design spreadsheet, building walls from a JSON floor plan, previewing local images before...
**Useful source sections:** Import: PromptImportFileAsync / PromptImportFilesAsync, Recipe: props from a CSV, Export: save the selection to disk.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts|Studio Tools - Plugin File IO - Import Files, Save Selection and Asset Prompts]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
