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
timestep | ID | left | top | height | width | img_height | img_width | parent
```
  * **timestep**: the time step of trajectory data
  * **ID**: the unique positive number of the cell
  * **left**: the minimum x-axis coordinate of the detection for the cell
  * **top**: the minimum y-axis coordinate of the detection for the cell
  * **height**: the height of the detection for the cell
  * **width**: the width of the detection for the cell
  * **img_height**: the height of the entire (background) image
  * **img_width**: the width of the entire (background) image
  * **parent**: the parent ID of the cell

- Statistics (csv): timestep with other categories (e.g., error, and mitosis)
```bash
timestep | 1st stat. | 2nd stat. | etc. | ... 
```
  * **timestep**: the time step of lineage data
  * **1st stat.**: the first quantified information
  * **2nd stat.**: the second quantified information
  * **etc.**: other values can be added here in order as other columns

- Image (png, jpg, or tif): background figures
  * Please see included example files.
  * [External library](https://github.com/seikichi/tiff.js) is used for TIF images.

{% include tip.html content="If TIF images do not quickly show, convert its file format from tif to png, or jpg before uploading via [importers][ov_preprocessing]." %}

{% include important.html content="Once images or images+etc are uploaded, refresh a browser (or click the system title) before newly uploading other data sets." %}

{% include links.html %}
