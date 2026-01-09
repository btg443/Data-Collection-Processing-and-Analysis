# Gender Bias in Predictive Models for Ischemic Heart Disease

This repository contains data and code used in a research project examining gender bias in predictive models for ischemic heart disease (IHD). The project investigates how different gender compositions in training data affect model performance and fairness using aggregated country–year–gender data.

## Repository Structure

- `final_ihd_dataset_with_preprocessing.csv`  
  Final analytical dataset including preprocessing steps such as handling missing values and adding variables not aggregated by gender.

- `final_ihd_dataset_without_preprocessing.csv`  
  Final analytical dataset created without preprocessing, used for comparison.

- `notebook for creating the dataset.ipynb`  
  Jupyter Notebook documenting data collection, merging, weighting, and preprocessing steps used to construct the final datasets.

- `notebook for predictions.ipynb`  
  Jupyter Notebook containing the modeling and prediction procedures.

- `README.md`  
  Overview and documentation of the repository.

## Data Sources

The project relies on publicly available secondary data obtained from the following sources. Raw data files are not redistributed in this repository; instead, links to the original data providers are provided below:

- World Health Organization (WHO): https://data.who.int/indicators  
- OECD Data Explorer: https://data-explorer.oecd.org/  
- Institute for Health Metrics and Evaluation (IHME): https://ghdx.healthdata.org/

## Notes

All data used in this project are aggregated at the country–year–gender level and do not contain any personal, sensitive, or confidential information. The repository is intended for academic and research purposes only.
