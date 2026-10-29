---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Mixed-Version Servers - Forward-Compatible Saves During Updates.md"
---
# Mixed-Version Servers - Forward-Compatible Saves During Updates — Development Guide

New practical guidance for [[04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Mixed-Version Servers - Forward-Compatible Saves During Updates|Mixed-Version Servers - Forward-Compatible Saves During Updates]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
When you publish, old servers keep running the old code. The Roblox docs are explicit: if you do not restart servers, players drift to the new version as old servers empty, and "if your underlying player data format changes, you should probably restart servers". Even when you do restart, the docs note that servers marked for shutdown stop receiving matchmaking but can still be joined through invites, teleports...
**Useful source sections:** The failure, step by step, Rule 1: an older server must never write newer data, Rule 2: make additions tolerant, not breaking.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Mixed-Version Servers - Forward-Compatible Saves During Updates, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Mixed-Version Servers - Forward-Compatible Saves During Updates and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Mixed-Version Servers - Forward-Compatible Saves During Updates|Mixed-Version Servers - Forward-Compatible Saves During Updates]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
