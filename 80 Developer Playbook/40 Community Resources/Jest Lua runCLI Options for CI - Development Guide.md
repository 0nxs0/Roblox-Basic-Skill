---
kind: development-companion
category: "40 Community Resources"
source-note: "40 Community Resources/Testing QA and DevOps/Jest Lua runCLI Options for CI.md"
---
# Jest Lua runCLI Options for CI — Development Guide

New practical guidance for [[40 Community Resources/Testing QA and DevOps/Jest Lua runCLI Options for CI|Jest Lua runCLI Options for CI]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`runCLI(rootDir, options, projects)` takes an options table that mirrors Jest's command-line flags. The options below are listed on the Jest Lua CLI page. Pick a CI profile and a local profile and keep them in one module so nobody hand-edits flags.
**Useful source sections:** Options worth knowing, A profile module (original example), Rules of thumb.

## Apply it
Use this topic as part of **evaluate community ideas before adopting**.
- **Define the contract:** For Jest Lua runCLI Options for CI, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Compare each idea with official docs and test it in a disposable place.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Review provenance, license, maintenance, dependencies, and security.

## Validate before shipping
- **Expected path:** Build one small feature using Jest Lua runCLI Options for CI and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Confirm compatibility, remove unrelated code, and keep a rollback path.

## Connected work
- Source note: [[40 Community Resources/Testing QA and DevOps/Jest Lua runCLI Options for CI|Jest Lua runCLI Options for CI]]
- Category hub: [[80 Developer Playbook/40 Community Resources/_Development Hub|40 Community Resources development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow]], [[80 Developer Playbook/30 Official Roblox Docs/_Development Hub|30 Official Roblox Docs]]

> Verify provenance, license, maintenance, and compatibility before adopting community material.
