---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests.md"
---
# Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests|Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most bad AI Luau is not a model problem, it is a missing-context problem. A model that does not know your folder layout, your remote list or who owns the data will invent all three, and it will happily use APIs from 2016 because a lot of its training data is old forum code. A prompt that ships a small context pack, names the exact APIs, forces a server/client split and asks for tests turns "looks right" code into...
**Useful source sections:** 1. Send a context pack, not a wish, 2. Name the APIs you want, 3. Force the server/client split.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Claude MCP AI Workflow/Community Knowledge/Flow - Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests|Prompting AI for Correct Roblox Code - Context Packs, API Names and Acceptance Tests]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
