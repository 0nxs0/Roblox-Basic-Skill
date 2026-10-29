---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Data Backend/Community Knowledge/Testable Save Layer - Fake DataStores and Failure Injection.md"
---
# Testable Save Layer - Fake DataStores and Failure Injection — Development Guide

New practical guidance for [[04 Networking Data and Servers/Data Backend/Community Knowledge/Testable Save Layer - Fake DataStores and Failure Injection|Testable Save Layer - Fake DataStores and Failure Injection]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Most save bugs only show up when something fails: a throttled write, a transform that runs twice, a server that dies mid-save. You cannot make the real DataStoreService fail on demand, and testing against it in Studio writes to real (Studio-scoped) data and costs budget. The fix is architectural: your save module talks to a store interface, and tests swap in a fake that you can tell to throw, delay or race. This...
**Useful source sections:** Step 1: inject the store, Step 2: a fake that behaves like the real thing, Step 3: the tests that matter.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Testable Save Layer - Fake DataStores and Failure Injection, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Testable Save Layer - Fake DataStores and Failure Injection and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Data Backend/Community Knowledge/Testable Save Layer - Fake DataStores and Failure Injection|Testable Save Layer - Fake DataStores and Failure Injection]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
