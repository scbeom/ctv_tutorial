---
title: Input files
tags: [file_format, quick_start]
keywords: input format
sidebar: mydoc_sidebar
permalink: ov_inputfile.html
folder: overview
summary: Input formats of CellTrackVis include text and image data.
---

## File format
- Trajectories with lineages (csv): bounding boxes with parent-child relationships
```bash
timestep | ID | left | top | height | width | x1 | x2 | x3 | x4 | parent
```
  * **timestep**: time step when the cell currently exists
  * **ID**: an unique positive number of the cell
  * **left**: the minimum x-axis coordinate of the detection for the cell
  * **top**: the minimum y-axis coordinate of the detection for the cell
  * **height**: the length of the detection for the cell
  * **width**: the width of the detection for the cell
  * **x1-x4**: uncertainty or confident of detection - dummy number (-1) at the moment
  * **parent**: the parent ID of the cell

- Statistics (csv): timestep with other categories (e.g., error, and mitosis)
```bash
timestep | num of cells | num of mitosis | MSE | ... 
```

- Image (png, jpg, or tif): background figures
  * Please see included example files.
  * [External library](https://github.com/seikichi/tiff.js) is used for tif images.

{% include note.html content="After uploading an image folder, wait a bit to plot image backgrounds on trajectory view. The processing time depends on users' or server's environments." %}

{% include tip.html content="If tif images do not quickly show, convert its file format from tif to png, or jpg before uploading via [preprocessors][ov_preprocessing]." %}

## Details

- 3D or multi-channel tif image

{% include image.html file="ov_multi_tif.png" caption="3D or multi-channel tif images. This example has 29 images in a tif file." max-width="500" %}

* Buttons for changing images in a tif image appears when pausing animation (in lineage view).

{% include links.html %}
