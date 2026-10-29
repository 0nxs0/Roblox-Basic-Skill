---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Git Version Control/Community Knowledge/Rojo, VS Code and luau-lsp - Local Setup from Zero.md"
---
# Rojo, VS Code and luau-lsp - Local Setup from Zero — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Git Version Control/Community Knowledge/Rojo, VS Code and luau-lsp - Local Setup from Zero|Rojo, VS Code and luau-lsp - Local Setup from Zero]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Writing Roblox code in VS Code gives you Git, real search, multi-cursor editing, AI agents in the terminal, and type checking that understands your whole game tree. The classic stack is Rojo (syncs files into Studio), the luau-lsp language server (autocomplete, types, diagnostics), and a toolchain manager to pin versions. Roblox's built-in Script Sync is now an alternative to Rojo for scripts (Script Sync vs Rojo...
**Useful source sections:** 1. Pin tools with Rokit, 2. Studio plugin, 3. Project layout and file rules.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Rojo, VS Code and luau-lsp - Local Setup from Zero, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Rojo, VS Code and luau-lsp - Local Setup from Zero and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Git Version Control/Community Knowledge/Rojo, VS Code and luau-lsp - Local Setup from Zero|Rojo, VS Code and luau-lsp - Local Setup from Zero]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
