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
timestep | id | left | top | height | width | x1 | x2 | x3 | x4 | parent
```

- Statistics (csv): timestep with other categories (e.g., error, and mitosis)
```bash
timestep | ... | ... | ... 
```

- Image (png, jpg, or tif): background figures

    * Please see included example files.

{% include note.html content="After uploading an image folder, wait a bit to plot image backgrounds on trajectory view. It also depends on users' or server's environments." %}

{% include tip.html content="If tif images do not quickly show, convert its file format from tif to png, or jpg before uploading." %}

## Details

Editing is being processed due to some changes of CellTrackVis.

{% include links.html %}
