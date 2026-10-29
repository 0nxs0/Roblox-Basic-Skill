---
kind: development-companion
category: "01 Start Here"
source-note: "01 Start Here/Community Knowledge/First RemoteEvent - Button on the Client, Reward on the Server.md"
---
# First RemoteEvent - Button on the Client, Reward on the Server — Development Guide

New practical guidance for [[01 Start Here/Community Knowledge/First RemoteEvent - Button on the Client, Reward on the Server|First RemoteEvent - Button on the Client, Reward on the Server]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Sooner or later a player presses something on their screen (a GUI button, a key) and the result must be real for everyone: coins, a door opening, an attack. Clients cannot do that alone, so they ask the server through a RemoteEvent, and the server checks and acts. Getting this one pattern right also gets your first anti-exploit habit right: never trust what the client sends.
**Useful source sections:** The three pieces, Client: ask, Server: check, then act.

## Apply it
Use this topic as part of **connect learning to playable results**.
- **Define the contract:** For First RemoteEvent - Button on the Client, Reward on the Server, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Choose a learning goal and prove it in a small vertical slice; record prerequisites and next steps.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Practice references in a disposable place and note version assumptions.

## Validate before shipping
- **Expected path:** Build one small feature using First RemoteEvent - Button on the Client, Reward on the Server and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Can a new developer produce a testable feature?

## Connected work
- Source note: [[01 Start Here/Community Knowledge/First RemoteEvent - Button on the Client, Reward on the Server|First RemoteEvent - Button on the Client, Reward on the Server]]
- Category hub: [[80 Developer Playbook/01 Start Here/_Development Hub|01 Start Here development hub]]
