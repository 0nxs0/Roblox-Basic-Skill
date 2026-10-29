---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls.md"
---
# AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls|AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Icons and thumbnails decide whether anyone clicks, and many Roblox devs now use AI image tools to make them. That can work, but there are three traps: images that misrepresent the game, images that copy other people's characters or brands, and images you cannot claim as your own work. This note is the safe workflow; for composition and click-through craft see Thumbnail Composition and Value Design and Game Icon...
**Useful source sections:** The Roblox specs you design for, A workflow that keeps the art honest, What to avoid.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls|AI Images for Thumbnails and Icons - Workflow, Accuracy Rules and Pitfalls]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
