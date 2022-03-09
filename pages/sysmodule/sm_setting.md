---
title: Setting view
tags: [file_format]
keywords: setting
sidebar: mydoc_sidebar
permalink: sm_setting.html
folder: sysmodule
summary: This page describes how to use the Setting view of CellTrackVis.
---

## Data upload

{% include image.html file="setting_buttons.png" caption="Buttons for uploading tracking results" max-width="500" %}

Cell tracking results are uploaded through buttons: 

* File: a csv file containing trajectory+lineage information 
* Statistic file: a csv file containing quantified information such as errors, the number of cells, and the number of mitosis
    * Each file must be in the "data" folder.
    * If there is no background image, set the lowest transparency (black).
    * Successfully loaded data will be appeared top of the buttons.

* Image: a folder having the sequence of background images
    * "Your image folder" must be in the existing "images" folder.
    * When uploading an image folder,
        * Refresh the web browser before studying other data sets.

{% include important.html content="Upload the trajectory file after uploading images." %}

## Split functions for trajectory view

{% include image.html file="setting_modes.png" caption="Modes for playing on trajectory view" max-width="800" %}

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
  * Cell vector:

## Mini map for trajectory view

{% include image.html file="setting_minimap.png" caption="Modes for playing on trajectory view" max-width="300" %}

* Mini map
    * Zoomed region is navigated in this minimized map.

{% include links.html %}
