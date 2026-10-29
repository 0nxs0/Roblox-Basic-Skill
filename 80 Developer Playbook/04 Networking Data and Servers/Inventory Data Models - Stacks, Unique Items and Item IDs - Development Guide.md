---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Inventory Data Models - Stacks, Unique Items and Item IDs.md"
---
# Inventory Data Models - Stacks, Unique Items and Item IDs — Development Guide

New practical guidance for [[04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Inventory Data Models - Stacks, Unique Items and Item IDs|Inventory Data Models - Stacks, Unique Items and Item IDs]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
An inventory has two kinds of things in it: fungible items where any copy equals any other (50 wood, 12 potions) and unique items that carry their own state (a sword with +3 enchant and 40% durability, a pet with a rolled trait). Storing both the same way is the root of most inventory pain: either you bloat the save with thousands of identical records, or you lose the per-item state that trading and anti-dupe...
**Useful source sections:** Three layers, Generating item IDs, Operations as small pure functions.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Inventory Data Models - Stacks, Unique Items and Item IDs, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Inventory Data Models - Stacks, Unique Items and Item IDs and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Inventory Data Models - Stacks, Unique Items and Item IDs|Inventory Data Models - Stacks, Unique Items and Item IDs]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
