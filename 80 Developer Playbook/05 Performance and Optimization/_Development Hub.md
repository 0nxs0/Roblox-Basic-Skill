---
kind: development-category-hub
category: "05 Performance and Optimization"
---
# 05 Performance and Optimization — Development Hub

This hub contains 72 new development companions, one for each existing Markdown note in **05 Performance and Optimization**. Each links to its source and adds implementation and validation guidance.

## Focus
Use this material to measure before tuning.

## Build loop
1. Capture a baseline, isolate one bottleneck, change one thing, and compare the same workload.
2. Use profiler evidence; watch memory, event frequency, replication, and worst-case scenes.
3. Record before/after measurements and test a low-end device under load.

## Connected disciplines
- [[80 Developer Playbook/03 Scripting and Systems/_Development Hub|03 Scripting and Systems]]
- [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]]
- [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]]

## New guides
- [[80 Developer Playbook/05 Performance and Optimization/BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame - Development Guide|BulkMoveTo - Moving Hundreds of Anchored Parts Per Frame]]
- [[80 Developer Playbook/05 Performance and Optimization/Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity - Development Guide|Collision Property Tuning - CanCollide, CanQuery, CanTouch and CollisionFidelity]]
- [[80 Developer Playbook/05 Performance and Optimization/Lean ReplicatedStorage - Join Payload Audit and On-Demand Delivery - Development Guide|Lean ReplicatedStorage - Join Payload Audit and On-Demand Delivery]]
- [[80 Developer Playbook/05 Performance and Optimization/Client Tween Volume - Hundreds of Tweens vs One Update Loop - Development Guide|Client Tween Volume - Hundreds of Tweens vs One Update Loop]]
- [[80 Developer Playbook/05 Performance and Optimization/Destroy vs Parent nil vs Debris - Teardown Without Spikes - Development Guide|Destroy vs Parent nil vs Debris - Teardown Without Spikes]]
- [[80 Developer Playbook/05 Performance and Optimization/Dirty Flags and task.defer - Coalescing Many Changes into One Update - Development Guide|Dirty Flags and task.defer - Coalescing Many Changes into One Update]]
- [[80 Developer Playbook/05 Performance and Optimization/Set Parent Last - Instance Creation Order and Template Cloning - Development Guide|Set Parent Last - Instance Creation Order and Template Cloning]]
- [[80 Developer Playbook/05 Performance and Optimization/Spatial Query Cost - Raycast, Bounds Queries and GetPartsInPart - Development Guide|Spatial Query Cost - Raycast, Bounds Queries and GetPartsInPart]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs - Development Guide|Speed - Asset Size Rules - Texture Pixels, Mesh Triangles, Audio Length and Duplicate IDs]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Case Study - Fixing a Laggy Obby - Development Guide|Speed - Case Study - Fixing a Laggy Obby]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Case Study - Fixing a Laggy Pet Simulator - Development Guide|Speed - Case Study - Fixing a Laggy Pet Simulator]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Case Study - Fixing a Laggy Shooter - Development Guide|Speed - Case Study - Fixing a Laggy Shooter]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Case Study - Fixing a Laggy Tycoon - Development Guide|Speed - Case Study - Fixing a Laggy Tycoon]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Connection Leak Finder - Counting Live Connections by Tag - Development Guide|Speed - Connection Leak Finder - Counting Live Connections by Tag]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes - Development Guide|Speed - Pathfinding Cost - Request Budgets, Path Caching and Shared Routes]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Physics Object Budget - Assemblies, Loose Debris, Ragdolls and Constraint Counts - Development Guide|Speed - Physics Object Budget - Assemblies, Loose Debris, Ragdolls and Constraint Counts]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Player-Keyed Tables - The Most Common Server Memory Leak - Development Guide|Speed - Player-Keyed Tables - The Most Common Server Memory Leak]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Round Start Spikes - Map Loads, Mass Spawns and Teleport Bursts - Development Guide|Speed - Round Start Spikes - Map Loads, Mass Spawns and Teleport Bursts]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers - Development Guide|Speed - String Building Cost - Concatenation Loops, table.concat and buffer Writers]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Table vs buffer for Big In-Memory Data - Grids, Maps and Caches - Development Guide|Speed - Table vs buffer for Big In-Memory Data - Grids, Maps and Caches]]
- [[80 Developer Playbook/05 Performance and Optimization/Unions vs MeshParts - When CSG Costs More Than It Saves - Development Guide|Unions vs MeshParts - When CSG Costs More Than It Saves]]
- [[80 Developer Playbook/05 Performance and Optimization/Weak Tables and Instance Caches in Luau - Development Guide|Weak Tables and Instance Caches in Luau]]
- [[80 Developer Playbook/05 Performance and Optimization/Instance Count and Part Budgets - Development Guide|Instance Count and Part Budgets]]
- [[80 Developer Playbook/05 Performance and Optimization/StreamingEnabled Gotchas and Streaming-Safe Client Code - Development Guide|StreamingEnabled Gotchas and Streaming-Safe Client Code]]
- [[80 Developer Playbook/05 Performance and Optimization/Instance Streaming Deep Dive - Development Guide|Instance Streaming Deep Dive]]
- [[80 Developer Playbook/05 Performance and Optimization/Memory Leaks & Lifecycle Management - Development Guide|Memory Leaks & Lifecycle Management]]
- [[80 Developer Playbook/05 Performance and Optimization/Object Pooling Without Making a Mess - Development Guide|Object Pooling Without Making a Mess]]
- [[80 Developer Playbook/05 Performance and Optimization/Optimization - Development Guide|Optimization]]
- [[80 Developer Playbook/05 Performance and Optimization/Production Labs - Development Guide|Production Labs]]
- [[80 Developer Playbook/05 Performance and Optimization/Spatial Hash for Nearby Queries - Development Guide|Spatial Hash for Nearby Queries]]
- [[80 Developer Playbook/05 Performance and Optimization/Visual Scalability & Quality Tiers - Development Guide|Visual Scalability & Quality Tiers]]
- [[80 Developer Playbook/05 Performance and Optimization/BillboardGui Cost - Nametags, Health Bars and MaxDistance - Development Guide|BillboardGui Cost - Nametags, Health Bars and MaxDistance]]
- [[80 Developer Playbook/05 Performance and Optimization/Choosing MaxPlayers - Server Memory, CPU and Map Size - Development Guide|Choosing MaxPlayers - Server Memory, CPU and Map Size]]
- [[80 Developer Playbook/05 Performance and Optimization/Luau GC Pressure - What Allocates and How to Cut It - Development Guide|Luau GC Pressure - What Allocates and How to Cut It]]
- [[80 Developer Playbook/05 Performance and Optimization/Humanoid Cost Knobs for NPCs - States, EvaluateStateMachine and Humanoid-Free Rigs - Development Guide|Humanoid Cost Knobs for NPCs - States, EvaluateStateMachine and Humanoid-Free Rigs]]
- [[80 Developer Playbook/05 Performance and Optimization/RunService Event Choice - PreRender, PreSimulation, PostSimulation and Heartbeat - Development Guide|RunService Event Choice - PreRender, PreSimulation, PostSimulation and Heartbeat]]
- [[80 Developer Playbook/05 Performance and Optimization/Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup - Development Guide|Sound Instance Budget - Unique Clips, Voice Reuse and Cleanup]]
- [[80 Developer Playbook/05 Performance and Optimization/SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens - Development Guide|SurfaceGui Cost - PixelsPerStud, Signs and In-World Screens]]
- [[80 Developer Playbook/05 Performance and Optimization/Transparency Overdraw - Glass, Foliage Cards and DoubleSided Meshes - Development Guide|Transparency Overdraw - Glass, Foliage Cards and DoubleSided Meshes]]
- [[80 Developer Playbook/05 Performance and Optimization/UI Layout Churn - AutomaticSize, TextScaled and Layout Rebuilds - Development Guide|UI Layout Churn - AutomaticSize, TextScaled and Layout Rebuilds]]
- [[80 Developer Playbook/05 Performance and Optimization/ViewportFrame Cost - Item Previews Without Frame Drops - Development Guide|ViewportFrame Cost - Item Previews Without Frame Drops]]
- [[80 Developer Playbook/05 Performance and Optimization/Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster - Development Guide|Remote Send Rate - Batching, Deltas and When One Remote Is Not Faster]]
- [[80 Developer Playbook/05 Performance and Optimization/Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology - Development Guide|Shadow and Light Source Cost - CastShadow, Light Shadows and Lighting Technology]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - DataStore Request Budgeting at Scale - Server and Experience Limits - Development Guide|Speed - DataStore Request Budgeting at Scale - Server and Experience Limits]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join - Development Guide|Speed - First-Use Hitches - Preloading Animations and Sounds Without Bloating Join]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Initial Join Time - From Clicking Play to Player Control - Development Guide|Speed - Initial Join Time - From Clicking Play to Player Control]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - native in Practice - Picking Functions, Checking Code Size and Avoiding Deopts - Development Guide|Speed - native in Practice - Picking Functions, Checking Code Size and Avoiding Deopts]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Pre-Publish Performance Gate - Numbers to Pass Before Every Release - Development Guide|Speed - Pre-Publish Performance Gate - Numbers to Pass Before Every Release]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances - Development Guide|Speed - Scene Analysis Walkthrough - Script, Animation, Audio Memory and Unparented Instances]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Transparent Batching - Concurrent Marketplace and Catalog Lookups - Development Guide|Speed - Transparent Batching - Concurrent Marketplace and Catalog Lookups]]
- [[80 Developer Playbook/05 Performance and Optimization/Speed - Type Annotations and Runtime Speed - What Types Actually Change - Development Guide|Speed - Type Annotations and Runtime Speed - What Types Actually Change]]
- [[80 Developer Playbook/05 Performance and Optimization/Workspace Settings Audit - Performance-Relevant Properties - Development Guide|Workspace Settings Audit - Performance-Relevant Properties]]
- [[80 Developer Playbook/05 Performance and Optimization/Developer Console Memory Categories Explained - Development Guide|Developer Console Memory Categories Explained]]
- [[80 Developer Playbook/05 Performance and Optimization/MicroProfiler Reading Guide - Development Guide|MicroProfiler Reading Guide]]
- [[80 Developer Playbook/05 Performance and Optimization/Script Profiler, Native Code Gen and Luau Hot Paths - Development Guide|Script Profiler, Native Code Gen and Luau Hot Paths]]
- [[80 Developer Playbook/05 Performance and Optimization/Server Heartbeat, Ping and Bandwidth Monitoring - Development Guide|Server Heartbeat, Ping and Bandwidth Monitoring]]
- [[80 Developer Playbook/05 Performance and Optimization/Feature Design Template - Development Guide|Feature Design Template]]
- [[80 Developer Playbook/05 Performance and Optimization/Fixed-Rate Scheduler - Development Guide|Fixed-Rate Scheduler]]
- [[80 Developer Playbook/05 Performance and Optimization/Memory grows over time - Development Guide|Memory grows over time]]
- [[80 Developer Playbook/05 Performance and Optimization/Mobile FPS collapses - Development Guide|Mobile FPS collapses]]
- [[80 Developer Playbook/05 Performance and Optimization/Mobile Performance Deep Dive - Development Guide|Mobile Performance Deep Dive]]
- [[80 Developer Playbook/05 Performance and Optimization/Object Pool - Development Guide|Object Pool]]
- [[80 Developer Playbook/05 Performance and Optimization/Performance - Development Guide|Performance]]
- [[80 Developer Playbook/05 Performance and Optimization/PERFORMANCE & PROFILING - Development Guide|PERFORMANCE & PROFILING]]
- [[80 Developer Playbook/05 Performance and Optimization/Performance Audit Procedure - Development Guide|Performance Audit Procedure]]
- [[80 Developer Playbook/05 Performance and Optimization/Performance Budget Template - Development Guide|Performance Budget Template]]
- [[80 Developer Playbook/05 Performance and Optimization/Performance Engineering Operating System - Development Guide|Performance Engineering Operating System]]
- [[80 Developer Playbook/05 Performance and Optimization/Performance Log Template - Development Guide|Performance Log Template]]
- [[80 Developer Playbook/05 Performance and Optimization/Quality Tier Settings - Development Guide|Quality Tier Settings]]
- [[80 Developer Playbook/05 Performance and Optimization/Spatial Hash - Development Guide|Spatial Hash]]
- [[80 Developer Playbook/05 Performance and Optimization/VFX Performance, LOD & Pooling - Development Guide|VFX Performance, LOD & Pooling]]
- [[80 Developer Playbook/05 Performance and Optimization/Weather Performance Budgets - Development Guide|Weather Performance Budgets]]
