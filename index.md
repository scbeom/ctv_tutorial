---
title: "Getting started with the tutorial for analyzing cell behaviors and ancestries"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with the CellTrackVis tutorial.
---

## Introduction

CellTrackVis supports a quick and easy analysis of cell movements with relevant information.
Interconnected views help users effortlessly discover meaningful patterns of cell motions and divisions, and also each component is highly customizable for various biological tasks.

## Environment Setup

**Requirements:**
- MAC OS, Linux or Windows
- Python 3.7+

**Steps of using CellTrackVis:**

- Install Python ref to [Download Python](https://www.python.org/downloads/).
- Download the source codes and extract files.
- The directory of CellTrackVis shows the following structure:

```
  CellTrackVis
      |server.py
      |data
          |...
      |images
          |...
      |celltrackvis.html
```

- Run CelTrackVis server.

```
python server.py
```

- After running the server, CellTrackVis is available on the web browser (e.g., Chrome).

```
127.0.0.1:8000/celltrackvis.html
```

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

### (A) Setting view

* Trajectories with lineages, and Statistics upload
    * Each file must be in the "data" folder.
    * If there is no background image, set the lowest transparency.
* A sequence of background images uploaded
    * An image folder must be in the "images" folder.
    * When uploading an image folder,
        * Specify "width/height pixels" in the following pop-up boxes.
        * Upload the trajectory file after uploading images.
        * Refresh the web browser before studying other data sets.
* Split mode
    * For a detailed analysis in a specific area, trajectory view can be divided using "horizontal" or "vertical" lines.
* Mini map
    * Zoomed region is navigated by this

### (B) Trajectory view

* Cells selection
    * Cells of interest are selected and highlighted after clicking those.
    * Then, relevant lineages are also highlighted in the Lineage view.
* Zoom in and out
    * Region can be zoomed in and out using mouse scrolling.

### (C) Lineage view

* Time bar
    * Trajectories are changing by moving the time bar.
* Lineage
    * Trajectories and points of selected lineages are also highlighted.

### (D) Statistic view

* Statistics
    * Uploaded information such as errors, the number of mitosis, and the number of appeared cells are plotted by time.
* Direction
    * The number of cells having each velocity (direction) vector are plotted at the left-top.

## License
For academic use, this project is licensed under the GNU Lesser General Public License v3.0 - see the LICENSE file for details. For commercial use, please contact the authors.

{% include links.html %}
