---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Notification Toasts from the Server.md"
---
# Recipe - Notification Toasts from the Server — Development Guide

New practical guidance for [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Notification Toasts from the Server|Recipe - Notification Toasts from the Server]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Small pop-ups at the bottom of the screen: "Not enough coins", "Quest complete +50 XP", "You need a Red keycard". Almost every other recipe needs a way for the server to tell one player something privately. Changing shared text (a prompt's `ActionText`, a sign) leaks the message to everyone; chat system lines get noisy. A toast module gives every server system one line to call: `Notify.send(player, "text", "error")`.
**Useful source sections:** Where it goes, Server module, Client toasts.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Recipe - Notification Toasts from the Server, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Recipe - Notification Toasts from the Server and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Scripting/Community Knowledge/Recipe - Notification Toasts from the Server|Recipe - Notification Toasts from the Server]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
