---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Networking Security/Community Knowledge/Net - Server-Owned NPCs - Network Ownership for Moving NPCs.md"
---
# Server-Owned NPCs - Network Ownership for Moving NPCs — Development Guide

New practical guidance for [[04 Networking Data and Servers/Networking Security/Community Knowledge/Net - Server-Owned NPCs - Network Ownership for Moving NPCs|Server-Owned NPCs - Network Ownership for Moving NPCs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Unanchored NPCs (Humanoid enemies, pets, physics mounts, carts pushed by players) are handed to whichever nearby client the engine picks. The Roblox docs say this outright: ownership is assigned automatically by proximity and client hardware, and when a client owns a part "Roblox cannot verify physics calculations". For NPCs that means the owning client can teleport, freeze or fling them, and their `Touched`...
**Useful source sections:** The default and why it bites, Policy: server owns every gameplay NPC, The cost and how to soften it.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Server-Owned NPCs - Network Ownership for Moving NPCs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Server-Owned NPCs - Network Ownership for Moving NPCs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Networking Security/Community Knowledge/Net - Server-Owned NPCs - Network Ownership for Moving NPCs|Server-Owned NPCs - Network Ownership for Moving NPCs]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
