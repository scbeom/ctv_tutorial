---
title: Importers
sidebar: mydoc_sidebar
permalink: ov_preprocessing.html
folder: overview
summary: Importers are provided for dealing with various data types. 
---

{% include tip.html content="If your data already meet CellTrackVis format, please ignore this section and go to the next step." %}

## Cell Tracking Challenge (CTC) format

In the CTC folder, there are two importers (preprocessors) for the CTC format:

### rest2csv.py

The CTC format of cell tracking result is converted to CellTrackVis format.
- Usage: python rest2csv.py
  * Option: segmentation or tracking data 

### tif2jpg.py

Although tif image can be used directly, PNG, and JEPG are more efficient on web browsers.
- Usage: python tif2jpg.py
  * Option: scaling up of visibility (e.g., 1~1000)

{% include image.html file="pre_tif2jpg.png" caption="Conversion of tif images for visibility (Fluo-N2DH-GOWT1, CTC data)" max-width="750" %}  

- Note that image backgrounds are not mandatory in CellTrackVis. Please visit [CTC web page](http://celltrackingchallenge.net) for further details.

## 2D coordinate (CSV) format

This importer covert 2D points into CellTrackVis box forms:

### point2box.py

The point form, e.g., (x,y), is converted to CellTrackVis format.

 

{% include note.html content="Each preprocessor is temporary provided and will be moved into the integrated main code in stages after optimization." %}

{% include links.html %}
