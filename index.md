---
title: "Getting started with the tutorial for CellTrackVis"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with the CellTrackVis tutorial.
---

## Introduction

CellTrackVis supports a quick and easy analysis of cell movements with relevant information.
Interconnected views help users effortlessly discover meaningful patterns of cell motions and divisions, and also each component is highly customizable for various biological tasks.

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

## License
For academic use, this project is licensed under the GNU Lesser General Public License v3.0 - see the LICENSE file for details. For commercial use, please contact the authors.

{% include links.html %}
