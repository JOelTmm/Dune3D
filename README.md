# Dune3D

Blender assets for a Dune / Arrakis environment in a smooth stylized "Paul" aesthetic (modular smooth meshes, PBR materials, game-ready for 2.5D side-scroller).

## Folder structure

- `blends/` — All .blend files (main consolidated + optimized + modular pieces)
- `renders/` — Preview renders
- `docs/` — Reference documents (e.g. sandworm)
- `README.md` — This file

## Main assets

- `blends/Dune_Arrakis_Master.blend` — Full environment (terrain/dunes/cliffs/canyons/ruins/oasis/tech/underground/sandworm elements)
- `blends/Dune_Arrakis_Master_Optimized.blend` — Performance version (faces reduced, Arrakis lighting added)
- Modular: Environment_With_Skybox, Decor_Architecture, Decor_Nature_Props
- `blends/Sabre_Laser.blend` + `blends/perso V2.blend`
- `blends/Futurist-gun.blend` — Additional weapon

## Style & notes
- Smooth low-to-mid poly, shade smooth
- PBR (Principled BSDF)
- Side-scroll ortho camera
- Golden Arrakis sunset lighting

**Performance**: Terrain & skybox decimated to avoid too many faces (as requested).

## References
See `docs/Ver_des_Sables_Description.md` for Shai-Hulud / sandworm aggregated image refs and single-block description.
