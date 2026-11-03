# Racing Car Builder — Professional 3D Asset Specification
Version 1 | 3 November 2026

## Project goal
A commercially usable, original fictional modern open-wheel single-seater racing car, built physically by players from a bare monocoque. Assembly is the main game mechanic; racing tests the completed car.

## Visual acceptance standard
- Photorealistic professional motorsport workshop quality, NOT cartoon/stylised, primitive geometry, or blocky toy appearance.
- Physically based carbon fibre, machined metal, rubber, painted composite and transparent materials.
- Accurate-looking modern single-seater proportions, suspension and engineering detail without copying identifiable team branding, liveries, proprietary design or protected assets.
- Convincing at close-up inspection and in partially assembled states.

## Phase 1 deliverable — bare monocoque
A detailed editable 3D carbon-fibre survival cell, cockpit opening and internal seat, roll hoop, front bulkhead, side-impact contours, attachment hardpoints, exposed suspension pick-up points and detachable floor.
No fitted wheels or finished outer bodywork in the starting configuration.

## Mandatory component separation
Each detachable part is a separate named mesh or logical group, with correct pivot and attachment point:
- monocoque (fixed root)
- floor and undertray
- front suspension: upper/lower wishbones, uprights, pushrods, steering links, dampers
- rear suspension equivalents
- brake discs, calipers and hubs, separately for all corners
- wheel assemblies: rim, tyre, centre-lock nut
- steering wheel, seat and cockpit details
- power unit, gearbox, radiators and exhaust (later)
- nose cone, front wing, sidepods, engine cover and rear wing (later)
No permanently fused full-car mesh as the sole deliverable.

## Technical requirements
- Editable source: Blender .blend or interoperable FBX with object hierarchy, UVs and textures.
- Browser preview: optimised GLB/glTF, PBR materials and LOD or mobile-friendly derivative.
- Consistent units: metres; forward is negative Z, up Y; car centred on X.
- Separate low/medium/high-detail variants where appropriate. Avoid assuming an iPad can render the final desktop-quality asset unchanged.
- Parts have named mounting points, collisions or proxy volumes and snap-fit transforms for future touch drag-and-drop.
- Optimised textures and geometry for mobile preview without sacrificing desktop master quality.

## Commercial rights and provenance gate
Before purchasing, downloading into the project or publishing:
1. Identify original author and asset source.
2. Confirm commercial modification and redistribution rights for inclusion in an interactive game, including any required attribution.
3. Verify no third-party team marks, logos, sponsor marks or unlicensed replica elements.
4. Check whether model geometry and component hierarchy are actually editable and separate.
5. Check included texture rights and restrictions.
6. Record evidence of licence and purchase terms in repository asset register.
No candidate is approved by appearance alone.

## Acceptance tests
1. Close-up view looks like professional motorsport photography rather than a toy.
2. Bare chassis looks credible without wheels/bodywork.
3. Individual wheel, upright, brake and suspension components can be selected and hidden independently.
4. Touch rotation and zoom operate on iPad preview.
5. Fitting one wheel snaps it to its correct hub without moving unrelated components.
6. No unauthorised branding or uncertain asset rights.

## Current status
- Browser interaction proof of concept: working on iPad (wheel fit and touch rotation).
- Professional model: NOT YET sourced or licensed.
- Photorealistic garage: NOT YET implemented.
- Next task: assess candidate editable monocoque models against this checklist; record licence evidence and component separation before integration.
