---
title: "Getting started with the tutorial for CellTrackVis"
keywords: homepage
tags: [quick_start, introduction]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with CellTrackVis.
---

## Abstract

CellTrackVis supports a quick and easy analysis of cell movements with relevant information.
Interconnected views help users effortlessly discover meaningful patterns of cell motions and divisions, and also each component is highly customizable for various biological tasks.

- [Code and data](http://github.com/scbeom/celltrackvis/)

## Environment setup

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
      |celltrackvis.html
      |data
        |...
      |images
        |...
      |preprocessors
        |...
```

- Run CelTrackVis server.
```
  python server.py
```

- After running the server, CellTrackVis is available on the web browser (e.g., Chrome).
```
  127.0.0.1:8000/celltrackvis.html
```

## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

{% include links.html %}
