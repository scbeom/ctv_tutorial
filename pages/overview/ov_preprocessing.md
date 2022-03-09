---
title: Preprocessing
sidebar: mydoc_sidebar
permalink: ov_preprocessing.html
folder: overview
summary: Preprocessors are provided for dealing with various data types. 
---

{% include tip.html content="If you already have the same format data, ignore this section and go to the next step." %}
{% include note.html content="Each preprocessor is temporary provided and will be moved into the integrated main code in stages." %}

## Cell Tracking Challenge (CTC) format

In the CTC folder, there are two preprocessors:

### rest2csv

The CTC format results of cell tracking is converted to CellTrackVis format.
- Option 1: segmentation
- Option 2: tracking 

### tif2jpg

Although tif image can be used directly, png, and jpg are more efficient on web browsers.
- Note that image backgrounds are not mandatory.

Visit [CTC web page](http://celltrackingchallenge.net) for further details.

## Getting started

To get started directly, see [Quick start][index].

{% include links.html %}
