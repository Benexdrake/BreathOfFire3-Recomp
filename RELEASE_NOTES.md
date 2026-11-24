# BreathOfFire3 Recompiled release notes

## v0.1.0 - first release (SLES-01304, Europe)

- **16:9 widescreen** in field and battle, with culling hooks for object/tile screen-X so no polygons pop in or leave black wedges at the edges.
- **60 fps** instead of PAL 50 Hz (PAL timing is forced to NTSC 60 Hz; `PSX_FORCE_60HZ=0` restores 50 Hz).

Not yet tested: world map, towns, menus, FMV.

Save states from other builds do not load. Native memory-card saves are unaffected.
