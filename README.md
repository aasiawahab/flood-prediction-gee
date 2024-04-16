# Datasets for the flood prediction
This Jupyter notebook provides code for visualizing and preprocessing data for the Germany administrative boundary.

## Introduction
This repository contains a Jupyter notebook that demonstrates the visualization and preprocessing of data related to the administrative boundary of Germany. It utilizes various libraries and tools, including Google Earth Engine Python API and geemap.

## Data Collection and Preparation: 				       
The datasets required for the process of flood prediction will consist of both vector and raster data. The datasets are temperature, rainfall, historical flood data, distance from rivers, elevation, Topographic Position Index (TPI), slope, future precipitation, and future temperature. A total of 7 major causal factors will be used for flood prediction.

## Table of Contents

- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
- [Setup](#setup)
- [License](#license)
- [Contact](#contact)

## Getting Started
### Dependencies

Make sure to install the required dependencies before running the script:

```bash
conda create -n gee python
conda activate gee
conda install -c conda-forge mamba
mamba install -c conda-forge geemap
```

## Setup
Ensure you have the required libraries installed:
- `ee` (Earth Engine Python API)
- `geemap`
- `pandas`
- `matplotlib`

Additionally, authenticate Earth Engine by running `ee.Authenticate()` and initialize it with `ee.Initialize()`.

## License
This project is licensed under the [MIT License](LICENSE)
## Contact
If you have any questions, or feedback, or just want to get in touch, feel free to reach out via email:
- Email: aasiafjwu@gmail.com
