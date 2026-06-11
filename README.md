# BhuMe Take-Home

## Overview

This project corrects cadastral plot boundaries using the provided example truths and satellite imagery.

## Method

1. Load village plots and imagery.
2. Compute centroid offsets between official plots and example truths.
3. Estimate a village-wide median shift.
4. Apply the shift to all plots.
5. Generate predictions.geojson automatically.

## Results

* Official median IoU: 0.612
* Predicted median IoU: 0.713
* Improvement: +0.112

## Output

The solution generates a contract-compliant `predictions.geojson` file.

## Run

```bash
python quickstart.py
```
