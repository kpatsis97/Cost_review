# README: Jupyter Notebook for "From Data to Discovery: Technology Propels Speech-Language Research and Theory-Building in Developmental Science"

## Overview
This Jupyter Notebook accompanies the paper "From Data to Discovery: Technology Propels Speech-Language Research and Theory-Building in Developmental Science." The notebook provides a step-by-step workflow for data processing, cleaning, and visualization, reproducing key figures presented in the paper.

## Contents
- **Data Loading**: Reads in raw data files used in the study.
- **Data Cleaning**: Processes and standardizes data to ensure consistency and accuracy.
- **Data Visualization**: Generates figures and plots corresponding to those presented in the paper.

## Requirements
This notebook requires Python and several key libraries. It is recommended to use the provided `environment.yml` file to create a Conda environment with all necessary dependencies.

### Dependencies
The required Python packages include:
- pandas
- numpy
- matplotlib
- seaborn
- geopandas 
- pySankey 
- textwrap

To set up the environment, use:
```bash
conda env create -f environment.yml
conda activate speech_tools
```
Alternatively, install packages manually with:
```bash
pip install -r requirements.txt
```

## Data
- The dataset used in this notebook is provided in the repository or can be accessed as per the instructions in the paper.

## Contact
For questions or issues related to this notebook, please contact the corresponding author as indicated in the paper.

---

*This notebook is shared to support transparency and reproducibility in research. If using or adapting this notebook, please cite the original paper.*

