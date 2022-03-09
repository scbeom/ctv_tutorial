---
title: Input files
tags: [file_format]
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

{% include tip.html content="If tif images does not quickly show, convert its file format from tif to png, or jpg." %}

## Details

Editing is being processed due to some changes of CellTrackVis.

## Getting started

To get started directly, see [Quick start][index].

{% include links.html %}
