---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Server Engineering/Community Knowledge/Net - Custom Matchmaking - Signals, Weights and Server Attributes.md"
---
# Custom Matchmaking - Signals, Weights and Server Attributes — Development Guide

New practical guidance for [[04 Networking Data and Servers/Server Engineering/Community Knowledge/Net - Custom Matchmaking - Signals, Weights and Server Attributes|Custom Matchmaking - Signals, Weights and Server Attributes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
When someone presses Play, Roblox picks the public server they join. Most developers never touch that choice and then build MemoryStore matchmakers and teleports to fix things the built-in system can already do: keep new players with new players, group by language, prefer low ping, or send people to servers running a particular mode. Custom matchmaking (Creator Dashboard > Configurations > Custom matchmaking)...
**Useful source sections:** How a join is matched (docs), Default weights, Tuning with built-in signals only.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Custom Matchmaking - Signals, Weights and Server Attributes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Custom Matchmaking - Signals, Weights and Server Attributes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Server Engineering/Community Knowledge/Net - Custom Matchmaking - Signals, Weights and Server Attributes|Custom Matchmaking - Signals, Weights and Server Attributes]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
