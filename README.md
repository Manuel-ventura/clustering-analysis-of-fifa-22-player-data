## README for Clustering-FIFA-22

# Clustering Analysis of FIFA 22 Player Data

## Introduction

This project performs a clustering analysis on FIFA 22 player data. The dataset includes various attributes of players from FIFA 15 to FIFA 22, allowing for multiple comparisons across different game versions. The primary goal is to identify clusters of players with similar characteristics using the K-means clustering algorithm.
- About the dataset here: https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset

## Objectives

1. **Data Cleaning and Preparation:**
   - Load FIFA 22 player data and select relevant features for clustering.
   - Handle missing values to ensure a clean dataset for analysis.

2. **Feature Standardization:**
   - Standardize the selected features to ensure equal contribution to the clustering process.

3. **Dimensionality Reduction:**
   - Apply Principal Component Analysis (PCA) to reduce the dimensionality of the data while retaining the most significant variance.

4. **Optimal Number of Clusters:**
   - Use the elbow method to determine the optimal number of clusters for K-means clustering.

5. **K-means Clustering:**
   - Perform K-means clustering on the reduced data to group players into distinct clusters.

6. **Cluster Visualization:**
   - Visualize the clusters in a 2D PCA space to understand the distribution and separation of player groups.

7. **Cluster Characterization:**
   - Analyze the characteristics of each cluster by calculating the mean values of the original features for each group, providing insights into different types of players.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- Jupyter Notebook

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Clustering-FIFA-22.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Clustering-FIFA-22
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Clustering-FIFA-22.ipynb
   ```

2. Run the cells in the notebook to perform the clustering analysis step-by-step. The code is fully commented to help you understand each step of the process.

## Results

The analysis identified four distinct clusters of players based on their overall rating, potential, wage, value, and age. The PCA facilitated the visualization of these clusters, and each cluster's characteristics were analyzed to provide insights into different types of players.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

The dataset used in this project is provided by FIFA and can be found in the `players_22.csv` file.

---

Feel free to update the repository URL and any other specific details as needed.
