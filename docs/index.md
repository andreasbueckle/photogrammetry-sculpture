# Photogrammetry Files and Workflow Documentation
**Author**: Andreas Bueckle, [https://andreas-bueckle.com/](https://andreas-bueckle.com/)
**Date**: December 29, 2024

## Overview
In this project, a wooden sculaputr depicting (Virgin and Child with Saint Anne)[https://en.wikipedia.org/wiki/Virgin_and_Child_with_Saint_Anne] was photogrammetrized. The sculpture depicts a subject in Christian iconography. The 14th century wooden sculpture was stolen in 1973 and resurfaced in 2024, then returned to its original place.  

## Result

<model-viewer src="/models/anna_lod_1.glb" alt="3D model" auto-rotate camera-controls></model-viewer>

**Figure 1**. This LOD 1 model of the St. Anna sculpture features ~750,000 polygons and is ~30 MB large.

## Workflow
The following steps were taken: 

1. The sculpture was placed onto a wooden table in a large, naturally lit space.    
2. 326 raw images in the RAF format were taken with a Fujifilm mirrorless camera and a 23mm lens. 
3. All 326 images were imported into Realitt Capture and a 3D model was computed in ~5 hours on a laptop running Windows 11, 64 GB RAM, and a Nvidia A2000 GPU.

![](/docs/images/rc_capture.png)
**Figure 2**. A screenshot of Reality Capture, including the 3D view (left) and a view of one of the images used to construct the model (right).

4. The model was textured and exported using the official tutorial at [https://www.youtube.com/watch?v=kRD0rgCnOWQ](https://www.youtube.com/watch?v=kRD0rgCnOWQ).
5. The original model has 212 million polygons and was not exported. 
6. For a LOD 0 export (highest resolution), the export out of Reality Capture was used (10 million polygons). LOD 1 (lower resolution) was exported using Blender to combine mesh and textures  resized in Photoshop.   

## Software 
- Reality Capture
- Blender 4.3.2

## Hardware
- Fujifilm XT3
- Fujifilm XF 23mm F2 WR