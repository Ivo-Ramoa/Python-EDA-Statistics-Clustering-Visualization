# Python EDA, Statistics, Clustering & Visualization

Data Science project focused on **exploratory data analysis, statistical analysis, clustering and interactive data visualization using Python**.

The project analyses a dataset related to public-service performance and citizen interactions, combining descriptive and inferential statistics with unsupervised machine learning and interactive Plotly dashboards.

## Project Files

- [View Project Presentation](presentation.pdf)
- [View Jupyter Notebook](tp2-a1.ipynb)
- [Dashboard](dashboard_igov.html)
- [Complete Dashboard](igov_dashboard_todos_graficos.html)
- [Dataset](Dataset-iGov.csv)

> The dashboards are exported as standalone HTML files and can be downloaded and opened directly in a web browser for interactive exploration.

## Project Overview

The project covers a complete exploratory and statistical analysis workflow:

- Dataset inspection and data quality analysis
- Descriptive statistics
- Distribution analysis
- Normality testing
- Correlation analysis
- Statistical hypothesis testing
- Probability distribution modelling
- Temporal analysis
- K-Means clustering
- Cluster validation
- Principal Component Analysis (PCA)
- Interactive Plotly dashboards

## Dataset

The dataset contains:

- **200 records**
- **17 variables**
- Numerical and categorical features
- Operational, performance and citizen-service indicators

Example variables include:

- Resolution rate
- Response time
- Citizen satisfaction
- Interaction volume
- Abandonment rate
- Technical errors
- Transparency
- Citizen feedback
- KPI indicator

## Statistical Analysis

The project applies several statistical techniques, including:

### Descriptive Statistics

Analysis of:

- Count
- Minimum and maximum
- Mean
- Median
- Mode
- Quartiles
- Standard deviation
- Skewness
- Kurtosis

### Normality Analysis

Normality is evaluated using:

- Histograms and KDE
- Q-Q plots
- Shapiro-Wilk tests

### Probability Distributions

The analysis includes:

- **Poisson distribution** for technical-error counts
- **Binomial modelling** for resolution-rate success
- **Student's t-distribution** for confidence intervals

### Statistical Testing

Non-parametric **Kruskal-Wallis tests** are used to analyse differences between service channels.

Correlation analysis is also performed to explore relationships between numerical variables.

## Clustering

Unsupervised learning is applied using **K-Means clustering**.

The clustering process includes:

- Feature standardization
- Testing multiple values of `k`
- Silhouette Score
- Elbow Method
- Calinski-Harabasz Score
- Cluster profiling

The Silhouette analysis selected **k = 6** as the best configuration in the main analysis.

## PCA

**Principal Component Analysis (PCA)** is used to reduce the multidimensional dataset to two dimensions and visualize the resulting clusters.

This provides a visual representation of the segmentation identified by K-Means.

## Interactive Dashboards

Two interactive dashboards were created using **Plotly**.

They consolidate several parts of the analysis, including:

- Statistical distributions
- Correlation heatmaps
- KPI analysis
- Poisson and Binomial modelling
- Clustering results
- PCA visualization

The dashboards are provided as standalone HTML files.

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly
- Statsmodels
- Jupyter Notebook

## Repository Structure

    Python-EDA-Statistics-Clustering-Visualization/
    ├── Dataset-iGov.csv
    ├── dashboard_igov.html
    ├── igov_dashboard_todos_graficos.html
    ├── presentation.pdf
    ├── tp2-a1.ipynb
    ├── README.md
    ├── requirements.txt
    └── .gitignore

## Running the Project

Install the required dependencies:

    pip install -r requirements.txt

Then start Jupyter:

    jupyter notebook

Open:

    tp2-a1.ipynb

The exported dashboards can also be opened directly in any modern web browser.

## Author

Developed as part of the Data Science coursework at **IPVC - Escola Superior de Tecnologia e Gestão**.

- Ivo Ramoa
