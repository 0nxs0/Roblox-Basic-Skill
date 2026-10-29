---
kind: development-companion
category: "20 FBX Asset Library"
source-note: "20 FBX Asset Library/Asset Licenses and Credits.md"
---
# Asset Licenses and Credits — Development Guide

New practical guidance for [[20 FBX Asset Library/Asset Licenses and Credits|Asset Licenses and Credits]]. This companion adds a build and validation plan; use the linked source for full reference detail.

## Source-grounded context
Source | License | Resale in a bundle | Credit ---|---|:-:|--- Top G Originals (VFX meshes + textures) | Original work for this vault | ✅ | none needed Kenney (kenney.nl) | CC0 1.0 | ✅ | appreciated: "Kenney.nl" Poly Haven (polyhaven.com) | CC0 1.0 | ✅ ("even in a product you sell") | appreciated: Poly Haven + artist 100STYLE mocap (zenodo.org/records/8127870) | CC BY 4.0 | ✅ | required (see below) Roblox Creator...
**Useful source sections:** Required credits, Community knowledge sources, Checked and left out.

## Apply it
Use this topic as part of **track and validate 3D imports**.
- **Define the contract:** For Asset Licenses and Credits, write down behavior, inputs, state owner, visible result, and failure response.
- **Build a first slice:** Record source, license, scale, axis, rig, and use; validate a representative import.
- **Maintain it:** Separate tuning data from behavior, record assumptions, and provide cleanup or rollback before connecting more systems.
- **Project risk:** Keep collision and visual meshes purposeful and preserve provenance.

## Validate before shipping
- **Expected path:** Build one small feature using Asset Licenses and Credits and record setup and expected result.
- **Boundary case:** Test missing, invalid, repeated, delayed, or interrupted input where relevant.
- **Integration:** Test with neighboring systems and at target device/player scale.
- **Acceptance check:** Check orientation, materials, pivots, rig, collision, and runtime cost.

## Connected work
- Source note: [[20 FBX Asset Library/Asset Licenses and Credits|Asset Licenses and Credits]]
- Category hub: [[80 Developer Playbook/20 FBX Asset Library/_Development Hub|20 FBX Asset Library development hub]]
