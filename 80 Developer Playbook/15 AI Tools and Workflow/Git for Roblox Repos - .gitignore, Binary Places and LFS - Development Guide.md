---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Git Version Control/Community Knowledge/Git for Roblox Repos - .gitignore, Binary Places and LFS.md"
---
# Git for Roblox Repos - .gitignore, Binary Places and LFS — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Git Version Control/Community Knowledge/Git for Roblox Repos - .gitignore, Binary Places and LFS|Git for Roblox Repos - .gitignore, Binary Places and LFS]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roblox projects mix two very different kinds of data: text (Luau scripts, JSON/TOML config, project files) that Git handles perfectly, and binary blobs (`.rbxl` places, `.rbxm` models, meshes, textures, audio) that Git can store but cannot diff or merge. Repos that commit place files on every save balloon to gigabytes and produce unresolvable conflicts. The fix is a clear rule about what lives in Git, a good...
**Useful source sections:** What belongs in the repo, Starter .gitignore (own), Binary assets and Git LFS.

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Git for Roblox Repos - .gitignore, Binary Places and LFS, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Git for Roblox Repos - .gitignore, Binary Places and LFS and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Git Version Control/Community Knowledge/Git for Roblox Repos - .gitignore, Binary Places and LFS|Git for Roblox Repos - .gitignore, Binary Places and LFS]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
