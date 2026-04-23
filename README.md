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

## Documentation

See **DitchExtraction_UserManual.pdf** for detailed instructions, 
screenshots, and parameter descriptions.

## Usage

It is recommended that all tools be executed within the provided 
ArcGIS Pro project (`DitchExtraction.aprx`) to ensure proper path 
management and avoid broken data references.

## Contact 

Emily Guyu Yang 

emily.yang@duke.edu  

Duke University
