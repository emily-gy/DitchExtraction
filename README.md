# DitchExtraction Toolbox

An ArcGIS Pro toolbox for extracting drainage ditch features from 
user-supplied Digital Elevation Models (DEMs) in low-relief coastal 
landscapes.

## Overview

The toolbox contains three tools that run sequentially:

1. **Compute TPI and Hillshade** — Generates Topographic Position 
   Index (TPI) and hillshade rasters from the input DEM.
2. **Improve Boundary and Connectivity** — Refines thresholded ditch 
   rasters using morphological operations (Boundary Clean, Expand, 
   Shrink, Region Group).
3. **Generate Ditch Raster and Polylines** — Produces the final 
   binary ditch raster and vectorized ditch centerlines.

## Requirements

- ArcGIS Pro 3.X or later (developed and tested on ArcGIS Pro 3.6.0)
- Spatial Analyst extension
- Input: bare-earth DEM (LiDAR-derived recommended)

## Installation

> ⚠️ **Important:** Download the **entire repository**, not just the `.atbx` 
> toolbox file. The tools rely on supporting scripts, geodatabases, and an 
> ArcGIS Pro project file with pre-configured paths. Downloading the toolbox 
> alone will result in broken references and tool failures.

To download:

1. Click the green **Code** button at the top of this repository.
2. Select **Download ZIP**.
3. Extract the downloaded zip file to your preferred location.
4. Open `DitchExtraction.aprx` in ArcGIS Pro to access the toolbox.

## Usage

It is recommended that all tools be executed within the provided 
ArcGIS Pro project (`DitchExtraction.aprx`) to ensure proper path 
management and avoid broken data references.

## Documentation

See `DitchExtraction_UserManual.pdf` for detailed instructions, screenshots, 
and parameter descriptions.

## Contact 

**Author:** Emily Guyu Yang<br>
**Email:** emily.yang@duke.edu<br>
**Affiliation:** Duke University

## License

This toolbox is released under the MIT License. See `LICENSE` file for details.
