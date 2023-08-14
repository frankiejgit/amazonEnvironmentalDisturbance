# Environmental and Social Impact Assessment of Mining and Oil Projects in the Amazon Basin

## Overview

This project aims to analyze the environmental and social impacts of mining and oil projects in the Amazon basin. It involves processing tabular and geospatial data to evaluate the effects of these projects on environmental disturbance, indigenous communities, and key environmental areas.

## Project Structure

- **data/**: Contains the tabular and geospatial data files used in the analysis.
- **notebooks/**: Jupyter notebooks used for data pre-processing, geospatial analysis, and visualization.
- **reports/**: Output reports, visualizations, and summary documents.
- **environment.yml**: Conda environment file specifying required packages and dependencies.
- **README.md**: This file, providing an overview of the project.

## Requirements

- Python >= 3.8 
- Conda (recommended for managing dependencies)

## Setup

1. Clone this repository to your local machine.
2. Create a Conda environment using the provided `environment.yml` file:
3. Place your tabular and geospatial data files in the `data/` directory.

## Usage

1. Open the Jupyter notebooks in the `notebooks/` directory to run different analysis steps.
2. Follow the instructions in the notebooks to load, preprocess, and analyze the data.
3. Visualizations and reports will be generated and saved in the `reports/` directory.

## Project Steps

1. Data Preparation:
- Clean and preprocess tabular data.
- Organize geospatial data in shapefiles.

2. Geospatial Analysis:
- Use Geopandas and other libraries to perform spatial operations.
- Overlay project boundaries, protected areas, and indigenous territories.

3. Environmental Disturbance Assessment:
- Calculate disturbance metrics (deforestation, habitat fragmentation, etc.).
- Create visualizations to show the impact over time.

4. Social Impact Assessment:
- Analyze proximity of projects to indigenous communities.
- Assess changes in demographics and living conditions.

5. Key Environmental Areas Evaluation:
- Identify ecologically sensitive areas.
- Analyze project impact on these areas.

6. Visualization and Reporting:
- Create interactive maps and informative charts.
- Compile findings into a comprehensive report.

## Journal

### Date: 08/13/2023

* Began cleaning and normalizing the data provided by the Inter-American Dialogue about energy and mining projects occuring in the Amazon River Basin as of November 2021. The transformation and data preparation is recorded in `data_prep.ipynb` and the data was saved under the `data/` folder.

## Contributors

- Francisco Gonzalez


