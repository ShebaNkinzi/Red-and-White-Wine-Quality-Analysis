Wine Quality Data Mining Project

This project performs a comprehensive data mining and analysis on the Red and White Wine Quality dataset from the UCI Machine Learning Repository. It includes data cleaning, feature engineering, dimensionality reduction, and visualization to explore patterns in wine chemical properties and quality.

Objective
To analyze wine quality based on physicochemical features, apply preprocessing techniques, and use PCA and t-SNE for dimensionality reduction and clustering visualization.


Files Included

| File | Description |
|------|-------------|
| `wine_quality_analysis.ipynb` | Jupyter Notebook with full analysis and visualizations |
| `winequality-red.csv` | Red wine dataset (from UCI) |
| `winequality-white.csv` | White wine dataset (from UCI) |
| `README.md` | This file |

Technologies Used

- Python – Core programming
- Pandas – Data manipulation
- NumPy – Numerical operations
- Matplotlib & Seaborn – Data visualization
- Scikit-learn – PCA and t-SNE for dimensionality reduction


Key Tasks Completed

Data Cleaning
- Checked for missing values (none found)
- Detected and removed outliers using the IQR method
- Scaled features using `StandardScaler`

Feature Engineering
- Created new feature: `acidity_ratio = fixed_acidity / volatile_acidity`
- Discretized `quality` into 3 classes: `low`, `medium`, `high`

Dimensionality Reduction
- Applied PCA (Principal Component Analysis)
- Applied t-SNE (t-Distributed Stochastic Neighbor Embedding)
- Visualized clusters colored by wine quality and type

Visualization
- Scatter plots for PCA and t-SNE results
- Color-coded by wine quality and type

Reflection
- Compared PCA vs t-SNE in terms of interpretability, accuracy, and trade-offs

Sample Output

[t-SNE Plot](tSNE_wine_quality.png)  
Example: t-SNE visualization of wine quality clusters

Dataset Source: [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

Author
Sheba Nkinzi 
BSc Information Technology, Year 3
