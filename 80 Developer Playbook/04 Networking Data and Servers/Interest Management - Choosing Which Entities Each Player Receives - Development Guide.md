---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Networking Security/Community Knowledge/Net - Interest Management - Choosing Which Entities Each Player Receives.md"
---
# Interest Management - Choosing Which Entities Each Player Receives — Development Guide

New practical guidance for [[04 Networking Data and Servers/Networking Security/Community Knowledge/Net - Interest Management - Choosing Which Entities Each Player Receives|Interest Management - Choosing Which Entities Each Player Receives]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Once you replicate entities yourself (Net - Custom Entity Replication - Server Data, Client Models), sending every entity to every player scales as players x entities and collapses fast: 40 players x 500 NPCs x 10 Hz is 200,000 pose updates per second. Interest management (area of interest, relevance filtering) is the step that decides, per player, which entities they get and how often. Roblox already does this...
**Useful source sections:** Built-in interest management you already have, Step 1: a spatial grid on the server, Step 2: hysteresis, so entities do not flicker.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Interest Management - Choosing Which Entities Each Player Receives, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Interest Management - Choosing Which Entities Each Player Receives and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Networking Security/Community Knowledge/Net - Interest Management - Choosing Which Entities Each Player Receives|Interest Management - Choosing Which Entities Each Player Receives]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
