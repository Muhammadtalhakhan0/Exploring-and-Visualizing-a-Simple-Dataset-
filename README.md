## Exploring and Visualizing a Simple Dataset (Iris)

**1: Objective**
The objective of this task is to explore and visualize the Iris dataset to understand
data trends, feature distributions, and relationships between different features using Python.

**2: Dataset Used**
- Iris Dataset
- Source: Seaborn library
- Total Records: 150
- Total Features: 5 (4 numerical features + 1 target class)

**3: Tools and Libraries**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

**4: Task Description**
In this task, exploratory data analysis (EDA) is performed on the Iris dataset.
The dataset is loaded and inspected using pandas. Summary statistics are generated
to understand the data, and different plots are created to visualize feature
distributions and relationships.

**5: Steps Performed**
- Loaded the Iris dataset using seaborn
- Displayed first rows using `head()`
- Checked dataset structure using `shape` and `info()`
- Generated summary statistics using `describe()`
- Created visualizations:
  - Scatter plot (Petal Length vs Petal Width) to see relationships between features
  - Histograms to analyze data distributions
  - Box plots to detect outliers and compare data spread

**6: Key Results and Findings**
- The dataset contains 150 records and has no missing values
- Four features are numerical and one column represents the species
- Petal features clearly separate the flower species
- Some outliers are visible in sepal width
- Visualizations help in understanding data patterns and feature importance

## Conclusion
This task shows the importance of exploratory data analysis before applying any
machine learning model. By analyzing and visualizing the Iris dataset, we can better
understand the data distribution and relationships between features.
