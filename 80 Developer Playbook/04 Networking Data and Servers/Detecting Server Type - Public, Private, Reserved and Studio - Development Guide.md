---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Server Engineering/Community Knowledge/Detecting Server Type - Public, Private, Reserved and Studio.md"
---
# Detecting Server Type - Public, Private, Reserved and Studio — Development Guide

New practical guidance for [[04 Networking Data and Servers/Server Engineering/Community Knowledge/Detecting Server Type - Public, Private, Reserved and Studio|Detecting Server Type - Public, Private, Reserved and Studio]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
The same place code often runs in four very different contexts: a public server anyone can join, a private (VIP) server a player paid for, a reserved server your matchmaker created for a match, and a Studio test. Many features should behave differently: owner-only admin commands in private servers, no lobby wait in a reserved match, no leaderboard writes from private servers where friends can farm each other....
**Useful source sections:** The two properties, Decision table, Private server ID is not a server instance ID.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Detecting Server Type - Public, Private, Reserved and Studio, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Detecting Server Type - Public, Private, Reserved and Studio and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Server Engineering/Community Knowledge/Detecting Server Type - Public, Private, Reserved and Studio|Detecting Server Type - Public, Private, Reserved and Studio]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
