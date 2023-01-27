---
title: Trajectory view
tags: [view, example]
sidebar: mydoc_sidebar
permalink: sm_trajectory.html
folder: sysmodule
summary: This page describes how to use the Trajectory view of CellTrackVis.
---

## Default state

{% include image.html file="traj_view.gif" caption="Example of the trajectory view" max-width="800" %}

* Current cell positions and vectors of direction to the next position are expressed by circles and arrows, respectively.
* Solid circles or lines denote currently living cells' locations or trajectories.
* Dotted circles or lines denote already disappeared cells' locations or trajectories.

## Cell and trajectory selection

{% include image.html file="traj_selection.gif" caption="Example of cell and trajectory selection" max-width="800" %}

* Cells of interest are selected and highlighted after clicking them. 
* Relevant lineages are also highlighted in the Lineage view.

## Zoom in and out

{% include image.html file="traj_zoom.gif" caption="Example of zoom functions" max-width="800" %}

* Region can be zoomed in and out using mouse scrolling.
* Region can be moved using mini map as well.


## Space partitioning

{% include image.html file="traj_partitioning.gif" caption="Example of space partitioning" max-width="800" %}

* Users can focus on some areas by selecting region of interest in the split mode.   
* Key map:
  * H: horizontal line
      - Make a horizontal line by clicking where you want to split.
  * V: vertical line
      - Make a vertical line by clicking where you want to split.
  * S: ready for selecting an area
      - Select a region by clicking the plane.
      - Histograms about the selected area appear.
  * M: delete line
      - Delete a line by hovering the line.

{% include note.html content="Current (split) sub-mode can be found under the key map instruction in the setting view." %}


{% include links.html %}
