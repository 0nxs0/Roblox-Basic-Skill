---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Join, Leave and Server Messages in Chat.md"
---
# Recipe - Join, Leave and Server Messages in Chat — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Join, Leave and Server Messages in Chat|Recipe - Join, Leave and Server Messages in Chat]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Coloured system lines in the chat window: "Alex joined the server", "Round starts in 10 seconds", "Sam found the golden key!". They make a server feel alive and are the cheapest way to announce game events. The key API fact: `TextChannel:DisplaySystemMessage` only works on the client (a LocalScript, or a Script with `RunContext = Client`), shows the line to that one user, and the docs say these messages are not...
**Useful source sections:** Where it goes, Server: a tiny announcer, Client: write the lines.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Join, Leave and Server Messages in Chat, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Join, Leave and Server Messages in Chat and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Join, Leave and Server Messages in Chat|Recipe - Join, Leave and Server Messages in Chat]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
