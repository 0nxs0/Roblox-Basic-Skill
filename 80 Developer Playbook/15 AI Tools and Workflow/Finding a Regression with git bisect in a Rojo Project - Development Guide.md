---
kind: development-companion
category: "15 AI Tools and Workflow"
source-note: "15 AI Tools and Workflow/Git Version Control/Community Knowledge/Flow - Finding a Regression with git bisect in a Rojo Project.md"
---
# Finding a Regression with git bisect in a Rojo Project — Development Guide

New practical guidance for [[15 AI Tools and Workflow/Git Version Control/Community Knowledge/Flow - Finding a Regression with git bisect in a Rojo Project|Finding a Regression with git bisect in a Rojo Project]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"It worked last week" is one of the most expensive bug reports in game dev: fifty commits landed since, several written by AI, and nobody knows which one broke the shop. `git bisect` turns that into a binary search: with 50 commits it needs about 6 tests, with 1,000 about 10. In a Rojo project every commit can be built into a place file, so you can bisect gameplay bugs, not just code errors. This only works if...
**Useful source sections:** Manual bisect (bug needs a playtest), Automatic bisect (bug shows up in a test), Bisect for "when did this change?".

## Apply it
Use this topic as part of **speed work while keeping human review**.
- **Define the contract:** For Finding a Regression with git bisect in a Rojo Project, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Give tools a bounded task and acceptance criteria; inspect generated changes in isolation.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Treat generated code as untrusted until reviewed; protect secrets and licenses.

## Validate before shipping
- **Expected path:** Build one small feature using Finding a Regression with git bisect in a Rojo Project and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check diffs, API versions, error paths, and tests.

## Connected work
- Source note: [[15 AI Tools and Workflow/Git Version Control/Community Knowledge/Flow - Finding a Regression with git bisect in a Rojo Project|Finding a Regression with git bisect in a Rojo Project]]
- Category hub: [[80 Developer Playbook/15 AI Tools and Workflow/_Development Hub|15 AI Tools and Workflow development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]], [[80 Developer Playbook/99 Vault Admin/_Development Hub|99 Vault Admin]]
