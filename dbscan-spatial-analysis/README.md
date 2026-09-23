# Spatial Clustering of Weather Stations using DBSCAN

A spatial data analysis project that clusters environmental/weather station data across Canada using the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm, to identify potential areas for agroclimatology and tourism.

## What it does

This project applies DBSCAN clustering to real environmental monitoring station data from Environment Canada, grouping stations based on their spatial density and environmental characteristics. The workflow includes:

- Downloading and cleaning real-world weather station data
- Exploratory data analysis of the dataset
- Applying DBSCAN clustering to identify meaningful spatial groupings
- Visualizing the resulting clusters to interpret potential applications in agroclimatology and tourism planning

## Tech stack

- Python
- pandas & NumPy (data processing)
- scikit-learn (DBSCAN implementation)
- Matplotlib (visualization)

## How to run

Open the notebook in Google Colab or Jupyter Notebook and run all cells in order. The dataset is automatically downloaded from a public data source within the notebook.

## Note

This project was originally developed as a course assignment for Spatial Analysis, applying unsupervised machine learning (clustering) to real-world environmental data.
