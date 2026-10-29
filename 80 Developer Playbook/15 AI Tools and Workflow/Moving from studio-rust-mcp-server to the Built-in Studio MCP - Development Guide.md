---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Moving from studio-rust-mcp-server to the Built-in Studio MCP.md"
---
# Moving from studio-rust-mcp-server to the Built-in Studio MCP — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Moving from studio-rust-mcp-server to the Built-in Studio MCP|Moving from studio-rust-mcp-server to the Built-in Studio MCP]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Many early AI-in-Studio setups (2025 tutorials, YouTube guides, older AGENTS.md files) use `Roblox/studio-rust-mcp-server`, the open-source reference MCP server that talked to Studio through a plugin. That repository is now archived and read-only with the notice that it is no longer actively developed; Roblox points users to the MCP server built into Studio. If your project instructions, onboarding docs or agent...
**Useful source sections:** Old vs new at a glance, Tool mapping, Migration checklist.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Moving from studio-rust-mcp-server to the Built-in Studio MCP, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Moving from studio-rust-mcp-server to the Built-in Studio MCP and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Moving from studio-rust-mcp-server to the Built-in Studio MCP|Moving from studio-rust-mcp-server to the Built-in Studio MCP]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
