### LuxCoreRender test scenes

This is a repository of complex LuxCoreRender test scenes in LuxCore SDL.

### Clone/Download

This repository uses git LFS, so you can **not** simply download it as a zip archive.

To clone it, you need to have git LFS installed: https://git-lfs.github.com/

Some of the scenes are also available as zip archives for instant download: 
https://github.com/LuxCoreRender/LuxCoreTestScenes/releases

### Authors

- LuxCoreRender-Wallpaper by Simon Wendsche (B.Y.O.B. at http://byob.carbonmade.com)
based on Psor cube scene;
- 2-glasses by arzaquna (https://github.com/LuxCoreRender/LuxCoreTestScenes)
- 3-spheres by David "Dade" Bucciarelli
- LuxMark-LuxBall by LuxRender project
- LuxMark-Mic by Vlad "SATtva" Miller (http://vladmiller.info/blog/index.php?comment=308)
- LuxMark-Hotel Scene designed by Peter "Piita" Sandbacka
- Prism by "Lighting_freak" (https://forums.luxcorerender.org/viewtopic.php?f=2&t=94)
- LuxCore 2.1 Benchmark by Charles Nandeya Ehouman (Sharlybg)
- Food scene by Charles Nandeya Ehouman (Sharlybg)
- HallBench scene by Charles Nandeya Ehouman (Sharlybg)
- PointinessExamples by Egert Kanep
- ProceduralLeaves by Provisory

### License

This software is released under Apache License Version 2.0 (see COPYING.txt file).

### Guidelines

New scenes should include:
- "readme.txt" mentioning the author and LuxCore version the scene was created with
- Scene in the native format of the 3D software it was created with, e.g. .blend for Blender.
  If possible, save the native format in compressed form and pack any required assets into it
- "LuxCoreScene" folder containing the scene in LuxCore text format (render.cfg, scene.scn, meshes as .ply, textures as .png/.exr).
  The FILESAVER engine can be used to generate these files
- Rendered result as "reference.png", created either within the 3D software or from standalone LuxCore
