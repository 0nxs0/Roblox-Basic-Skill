---
kind: development-companion
category: "16 Fast Game Kit"
source-note: "16 Fast Game Kit/Starter Code/Starter Code - 06 Analytics Events.md"
---
# Starter Code - 06 Analytics Events — Development Guide

New practical guidance for [[16 Fast Game Kit/Starter Code/Starter Code - 06 Analytics Events|Starter Code - 06 Analytics Events]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Custom fields use the keys `Enum.AnalyticsCustomFieldKeys.CustomField01.Name` to `CustomField03.Name` (strings `"CustomField01"`...). Flow types are `Enum.AnalyticsEconomyFlowType.Source` / `Sink`. Recommended transaction types are the `.Name` of `Enum.AnalyticsEconomyTransactionType` items: `IAP`, `Shop`, `Gameplay`, `ContextualPurchase`, `TimedReward`, `Onboarding`.
**Useful source sections:** Why this matters, Exact API (checked against the `AnalyticsService` reference), The code.

## Apply it
Use this topic as part of **assemble small loops from understood parts**.
- **Define the contract:** For Starter Code - 06 Analytics Events, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Build one playable loop, separate configuration from behavior, and document replacement points.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check dependencies, licenses, authority, and lifecycle before reuse.

## Validate before shipping
- **Expected path:** Build one small feature using Starter Code - 06 Analytics Events and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Run in a clean place and swap one component safely.

## Connected work
- Source note: [[16 Fast Game Kit/Starter Code/Starter Code - 06 Analytics Events|Starter Code - 06 Analytics Events]]
- Category hub: [[80 Developer Playbook/16 Fast Game Kit/_Development Hub|16 Fast Game Kit development hub]]
