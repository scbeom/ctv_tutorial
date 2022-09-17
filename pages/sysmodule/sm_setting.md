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

* Trajectory file: a csv file containing trajectory+lineage information
  * Loaded trajectories and/or lineages are appeared in the trajectory view.
  * Set the lowest transparency (black) if there is no background image in the current analysis.

{% include image.html file="setting_trajectory.gif" max-width="800" %}
 

* Statistic file: a csv file containing quantified information such as errors, the number of cells, and the number of mitosis
    * Loaded statistics are appeared in the statistic view.

{% include image.html file="setting_statistic.gif" max-width="800" %}


* Image file: a folder having the sequence of background images
    * Loaded images are appeared in the trajectory view as backgrounds.

{% include image.html file="setting_image.gif" max-width="800" %}


{% include important.html content="Trajectory with lineage files must be in the 'data' folder, and image files must be in the 'image' folder." %}

## Split functions for trajectory view

{% include image.html file="setting_modes.gif" caption="Modes for playing on trajectory view" max-width="800" %}

* Split mode
    * For a detailed analysis in a specific area, trajectory view can be divided using "horizontal" or "vertical" lines.

{% include tip.html content="More specific usages can be found in [Example][ex_example_1]." %}

## Options for trajectory view

{% include image.html file="setting_options.png" caption="Modes for playing on trajectory view" max-width="400" %}

* Bar
  * Image: the transparency of image backgrounds 
  * Circle: the size of (cell) circles
  * Thickness: the thickness of trajectories (with vector arrows)

* Tick box
  * Cell point: (cell) circle plot or not
  * All point: (disappeared cell at current time) circle plot or not
  * Cell ID: unique identity plot or not
    * Format: id(birth time)
  * Cell vector: velocity vectors (to the next time step)
  * Cell trajectory: (currently appeared) cell's trajectories
  * All trajectory: (previous and current) cell's all trajectories
  * Map grid: horizontal and vertical lines for helping measurements

## Mini map for trajectory view

{% include image.html file="setting_minimap.png" caption="Modes for playing on trajectory view" max-width="300" %}

* Mini map
    * Zoomed region is navigated in this minimized map.

{% include links.html %}
