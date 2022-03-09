---
title: Input files
tags: [file_format]
keywords: input format
sidebar: mydoc_sidebar
permalink: ov_inputfile.html
folder: overview
summary: Input formats of CellTrackVis include text and image data.
---

## Input

- Trajectories with lineages (.csv): bounding boxes with parent-child relationships
```bash
timestep | id | left | top | height | width | x1 | x2 | x3 | x4 | parent
```

- Statistics (.csv): timestep with other categories (e.g., error, and mitosis)
```bash
timestep | ... | ... | ... 
```

- Image (.png): background figures

    * Please see included example files.

## Details

### Trajectory file

### Lineage file

### Image file

### Statistic file

{% include links.html %}
