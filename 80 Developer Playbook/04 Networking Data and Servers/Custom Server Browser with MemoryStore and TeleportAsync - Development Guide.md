---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Server Engineering/Community Knowledge/Custom Server Browser with MemoryStore and TeleportAsync.md"
---
# Custom Server Browser with MemoryStore and TeleportAsync — Development Guide

New practical guidance for [[04 Networking Data and Servers/Server Engineering/Community Knowledge/Custom Server Browser with MemoryStore and TeleportAsync|Custom Server Browser with MemoryStore and TeleportAsync]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Roleplay games, hangouts and competitive lobbies often want a server list: pick a region-tagged server, a map, or "the one my squad is in". Roblox's own server list only shows basic info, so games build their own. The pieces are simple: every server advertises itself in a MemoryStore with a short TTL, a lobby reads the list, and a join uses `TeleportAsync` with `TeleportOptions.ServerInstanceId`. The older...
**Useful source sections:** Advertise (every game server), Read (lobby server, not clients), Join.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Custom Server Browser with MemoryStore and TeleportAsync, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Custom Server Browser with MemoryStore and TeleportAsync and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Server Engineering/Community Knowledge/Custom Server Browser with MemoryStore and TeleportAsync|Custom Server Browser with MemoryStore and TeleportAsync]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
