---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math.md"
---
# AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math|AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
AI is genuinely good at the boring half of design work: turning a messy idea into a structured one-pager, listing edge cases, generating a first pass of item tables and writing spreadsheet formulas. It is genuinely bad at the half that matters: knowing whether the numbers feel right, and doing arithmetic reliably in prose. The workflow below uses AI where it is strong and forces the numbers into a spreadsheet...
**Useful source sections:** 1. Design docs: AI as editor, not author, 2. Balancing: numbers live in a sheet, not in chat, 3. Prompts that work for balancing.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math|AI for Design Docs and Balancing Spreadsheets - Draft Fast, Check the Math]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
