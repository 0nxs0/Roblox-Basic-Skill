---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Networking Security/Community Knowledge/What a Client Controls on Its Own Character - Replication Exceptions.md"
---
# What a Client Controls on Its Own Character - Replication Exceptions — Development Guide

New practical guidance for [[04 Networking Data and Servers/Networking Security/Community Knowledge/What a Client Controls on Its Own Character - Replication Exceptions|What a Client Controls on Its Own Character - Replication Exceptions]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
"FilteringEnabled means client changes do not replicate" is true for most of the DataModel, and false for the one object exploiters care about most: their own character. Several systems deliberately let the owning client drive the server's copy so movement and animation feel instant. Every anti-exploit and combat check must start from this list, because anything on it is attacker-controlled input, not server truth.
**Useful source sections:** What does replicate from the owning client, What does not replicate, Design rules that follow.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For What a Client Controls on Its Own Character - Replication Exceptions, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using What a Client Controls on Its Own Character - Replication Exceptions and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Networking Security/Community Knowledge/What a Client Controls on Its Own Character - Replication Exceptions|What a Client Controls on Its Own Character - Replication Exceptions]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
