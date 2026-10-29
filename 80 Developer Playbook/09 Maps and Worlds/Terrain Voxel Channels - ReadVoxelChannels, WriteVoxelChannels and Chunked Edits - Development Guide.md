---
kind: development-companion
category: "09 Maps and Worlds"
source-note: "09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits.md"
---
# Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits — Development Guide

New practical guidance for [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits|Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
`ReadVoxels` and `WriteVoxels` work on two arrays, material and occupancy, and treat water as just another material. The newer channel methods split the data into SolidMaterial, SolidOccupancy and LiquidOccupancy, which is how the engine stores shorelines where rock and water share a voxel. If you edit terrain from code (biome painting, flooding a basin, draining a lake, procedural caves), the channel API lets...
**Useful source sections:** Rules that every voxel call shares (Engine API), The three channels, Example: flood everything below a water line.

## Apply it
Use this topic as part of **shape navigation within runtime budgets**.
- **Define the contract:** For Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set a traversal goal and landmark rhythm; test a greybox route before adding detail.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Plan streaming, spawns, sightlines, collision, accessibility, and memory together.

## Validate before shipping
- **Expected path:** Build one small feature using Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Test route clarity, streaming, respawn recovery, and low-end rendering.

## Connected work
- Source note: [[09 Maps and Worlds/Terrain Vegetation/Community Knowledge/Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits|Terrain Voxel Channels - ReadVoxelChannels, WriteVoxelChannels and Chunked Edits]]
- Category hub: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds development hub]]
- Related disciplines: [[80 Developer Playbook/05 Performance and Optimization/_Development Hub|05 Performance and Optimization]], [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]
