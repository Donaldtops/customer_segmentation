# Customer Segmentation Project

## Overview
This repository contains a customer segmentation project aimed at understanding customer behavior using Exploratory Data Analysis (EDA), Principal Component Analysis (PCA), and K-Means clustering. The main objective of this analysis is to segment customers based on their attributes and interactions with the business, enabling targeted marketing strategies and personalized customer experiences.

## Project Structure
- **data/**: Directory containing the datasets used for analysis.
- **notebooks/**: Directory containing Jupyter notebooks with the analysis workflow.
  - `01_data_preparation.ipynb`: Notebook for data preprocessing and exploration.
  - `02_feature_engineering.ipynb`: Notebook for feature engineering and transformation.
  - `03_pca.ipynb`: Notebook for Principal Component Analysis (PCA).
  - `04_kmeans.ipynb`: Notebook for K-Means clustering.
  - `05_visualization.ipynb`: Notebook for visualizing customer segments.
- **results/**: Directory containing visualizations and outputs generated during the analysis.
- **README.md**: This file, providing an overview of the project.

## Usage
To reproduce the analysis, follow these steps:
1. Ensure Python and necessary libraries are installed (requirements listed in `requirements.txt`).
2. Clone this repository to your local machine.
3. Navigate to the `notebooks/` directory.
4. Open Jupyter Notebook and run each notebook in sequential order (`01_data_preparation.ipynb`, `02_feature_engineering.ipynb`, `03_pca.ipynb`, `04_kmeans.ipynb`, `05_visualization.ipynb`).
5. Customize the analysis as needed for your specific business context and dataset.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
