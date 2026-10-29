---
kind: development-companion
category: "10 3D Art and Materials"
source-note: "10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes.md"
---
# Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes — Development Guide

New practical guidance for [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes|Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
After a few months a Roblox project has hundreds of meshes, images and materials with names like `Meshes/rockfinal2`. Artists re-upload things that already exist, scripts grab the wrong version, and nobody knows which assets are licensed CC BY. A small library system fixes this at three levels: the cloud inventory (Asset Manager folders), the place (a fixed folder layout for source models) and metadata on the...
**Useful source sections:** Level 1: Asset Manager folders (cloud inventory), Level 2: the source-of-truth place layout, Level 3: tags and attributes as metadata.

## Apply it
Use this topic as part of **ship assets within visual and runtime budgets**.
- **Define the contract:** For Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Set scale, pivot, naming, materials, collision, and import conventions; validate one asset first.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Check texture memory, mesh complexity, rig compatibility, and licensing.

## Validate before shipping
- **Expected path:** Build one small feature using Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Compare at target distance and quality; verify interaction and performance.

## Connected work
- Source note: [[10 3D Art and Materials/3D Modeling Blender/Community Knowledge/Model - Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes|Art Asset Library in Studio - Asset Manager Folders, Tags and Attributes]]
- Category hub: [[80 Developer Playbook/10 3D Art and Materials/_Development Hub|10 3D Art and Materials development hub]]
- Related disciplines: [[80 Developer Playbook/09 Maps and Worlds/_Development Hub|09 Maps and Worlds]], [[80 Developer Playbook/11 VFX Lighting and Weather/_Development Hub|11 VFX Lighting and Weather]], [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library]]
