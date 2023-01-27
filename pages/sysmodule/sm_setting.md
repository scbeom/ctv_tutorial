---
title: Setting view
tags: [file_format, view]
keywords: setting
sidebar: mydoc_sidebar
permalink: sm_setting.html
folder: sysmodule
summary: This page describes how to use the Setting view of CellTrackVis.
---

## Data upload

Cell tracking results are uploaded through three buttons: 

{% include image.html file="setting_trajectory.gif" caption="Example of trajectory with lineage uploading" max-width="800" %}

* Trajectory file: a csv file containing trajectory+lineage information
  * Loaded trajectories and/or lineages are appeared in the trajectory view.
  * Set the lowest transparency (black) if there is no background image in the current analysis.


{% include image.html file="setting_statistic.gif" caption="Example of statistic uploading" max-width="800" %} 

* Statistic file: a csv file containing quantified information such as errors, the number of cells, and the number of mitosis
    * Loaded statistics are appeared in the statistic view.


{% include image.html file="setting_image.gif" caption="Example of image uploading" max-width="800" %}

* Image file: a folder having the sequence of background images
    * Loaded images are appeared in the trajectory view as backgrounds.


{% include important.html content="Trajectory with lineage files must be in the 'data' folder, and image files must be in the 'image' folder." %}

## Split functions for trajectory view

{% include image.html file="setting_modes.gif" caption="Example of the mode change" max-width="800" %}

* Split mode
    * For a detailed analysis in a specific area, trajectory view can be divided using "horizontal" or "vertical" lines.

{% include tip.html content="More specific usages can be found in [Examples][ex_example_1]." %}

## Option controller for trajectory view

{% include image.html file="setting_options.gif" caption="Example of option controller" max-width="800" %}

* Bar
  * Image: the transparency of image backgrounds 
  * Circle: the size of (cell) circles
  * Thickness: the thickness of trajectories (with vector arrows)

* Tick box
  * Cell point: toggle for positions of cells, which have not disappeared
  * All points: toggle for dotted circles on positions of all cells (disappeared at current time)
  * Cell label: toggle for cell labels composed of an identifier and the birth time
    * Format: id(birth time)
  * Cell vector: toggle for vectors of cell direction (to the next time step)
  * Cell trajectory: toggle for linked lines between previous and current positions of cells (currently appeared) 
  * All trajectories: toggle for dotted linked lines between previous and current positions of all cells (previous and current)
  * Map grid: toggle for grid lines on the entire area

## Mini map for trajectory view

{% include image.html file="setting_minimap.gif" caption="Example of the mini map" max-width="800" %}

* Mini map
    * Zoomed region is navigated using the minimized map.

{% include links.html %}
