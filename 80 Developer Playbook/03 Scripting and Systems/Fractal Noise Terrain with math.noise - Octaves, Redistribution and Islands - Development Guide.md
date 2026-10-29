---
kind: development-companion
category: "03 Scripting and Systems"
source-note: "03 Scripting and Systems/Procedural Generation/Community Knowledge/Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands.md"
---
# Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands — Development Guide

New practical guidance for [[03 Scripting and Systems/Procedural Generation/Community Knowledge/Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands|Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Procedural worlds, infinite runners, mining games and random biomes all start with a heightmap. Roblox ships Perlin noise as `math.noise`, but raw noise looks like gentle blobs. Amit Patel's Red Blob Games article on terrain from noise shows the small set of tricks that turn it into believable land: octaves, redistribution, terraces, two-map biomes and island shaping. This note maps each trick onto Luau and the...
**Useful source sections:** math.noise quirks (from the API reference), Step 1: octaves (fractal Brownian motion), Step 2: redistribution.

## Apply it
Use this topic as part of **build reliable Luau components**.
- **Define the contract:** For Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Specify inputs, outputs, state owner, lifecycle, and failure behavior before coding.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Make side effects explicit, clean connections, validate boundaries, and avoid hidden state.

## Validate before shipping
- **Expected path:** Build one small feature using Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test missing, repeated, and out-of-order input plus respawn and reset.

## Connected work
- Source note: [[03 Scripting and Systems/Procedural Generation/Community Knowledge/Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands|Fractal Noise Terrain with math.noise - Octaves, Redistribution and Islands]]
- Category hub: [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems development hub]]
- Related disciplines: [[80 Developer Playbook/04 Networking Data and Servers/_Development Hub|04 Networking Data and Servers]], [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/14 Testing and QA/_Development Hub|14 Testing and QA]]
