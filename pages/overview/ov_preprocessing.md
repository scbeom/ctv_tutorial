---
title: Preprocessing
sidebar: mydoc_sidebar
permalink: ov_preprocessing.html
folder: overview
summary: Preprocessors are provided for dealing with various data types. 
---

{% include tip.html content="If you already have the same format data, ignore this section and go to the next step." %}
{% include important.html content="Each preprocessor is temporary provided and will be moved into the integrated main code in stages after optimization." %}

## Cell Tracking Challenge (CTC) format

In the CTC folder, there are two preprocessors:

### rest2csv.py

The CTC format of cell tracking result is converted to CellTrackVis format.
- python rest2csv.py {tif path} {output}
  * Option 1: segmentation
  * Option 2: tracking 

### tif2jpg.py

Although tif image can be used directly, png, and jpg are more efficient on web browsers.
- Note that image backgrounds are not mandatory.

{% include note.html content="Visit [CTC web page](http://celltrackingchallenge.net) for further details." %}

{% include links.html %}
