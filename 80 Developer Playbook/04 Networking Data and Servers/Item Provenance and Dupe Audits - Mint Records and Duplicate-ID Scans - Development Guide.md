---
kind: development-companion
category: "04 Networking Data and Servers"
source-note: "04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans.md"
---
# Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans — Development Guide

New practical guidance for [[04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans|Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Session locking and atomic trades stop most duplication, but no game ships bug-free. When a dupe does happen, the question becomes: which copy is real, how many exist, and which code path made them? If every valuable item carries a unique id from birth and you log where ids come from, you can answer that in minutes. Without it, you are guessing from player reports. As one devforum reply puts it, stop duping...
**Useful source sections:** The provenance fields, Mint log (append-only), Detecting duplicates.

## Apply it
Use this topic as part of **make client-server flows authoritative**.
- **Define the contract:** For Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Draw the message flow; keep trusted state on the server, validate requests, and define timeouts.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Assume clients can lie and packets can arrive late; rate-limit costly work.

## Validate before shipping
- **Expected path:** Build one small feature using Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test two clients, bad values, duplicates, latency, disconnects, and save failures.

## Connected work
- Source note: [[04 Networking Data and Servers/Data Backend/Community Knowledge/Net - Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans|Item Provenance and Dupe Audits - Mint Records and Duplicate-ID Scans]]
- Category hub: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers development hub]]
- Related disciplines: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]], [[80 Developer Playbook/07 AI and Combat/_Development Hub|07 AI and Combat]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
