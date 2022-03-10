---
title: Input files
tags: [file_format, quick_start]
keywords: input format
sidebar: mydoc_sidebar
permalink: ov_inputfile.html
folder: overview
summary: Input formats of CellTrackVis include text and image data.
---

{% include note.html content="In this page, editing is being processed due to some changes of CellTrackVis. Contents could be changed." %}

## File format
- Trajectories with lineages (csv): bounding boxes with parent-child relationships
```bash
timestep | ID | left | top | height | width | x1 | x2 | x3 | x4 | parent
```

- Statistics (csv): timestep with other categories (e.g., error, and mitosis)
```bash
timestep | ... | ... | ... 
```

- Image (png, jpg, or tif): background figures

* Please see included example files.

* [External library](https://github.com/seikichi/tiff.js) is used for tif images.

{% include note.html content="After uploading an image folder, wait a bit to plot image backgrounds on trajectory view. It also depends on users' or server's environments." %}

{% include tip.html content="If tif images do not quickly show, convert its file format from tif to png, or jpg before uploading via [preprocessors][ov_preprocessing]." %}

## Details

- 3D or multi-channel tif image

{% include image.html file="ov_multi_tif.png" caption="3D or multi-channel tif images. This example has 29 images in a tif image file." max-width="500" %}

* Buttons for changing images in a tif image appears when pausing animation (in lineage view).

{% include links.html %}
