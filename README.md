# Exploring-and-Visualizing-a-Simple-Dataset

**Project Overview**

This project demonstrates basic data loading, structure exploration, and visualization techniques using Python libraries such as **pandas**, **matplotlib**, and **seaborn**. The goal is to explore the dataset, understand relationships between variables, and detect patterns like outliers and distribution spread.

## Dataset

- **File**: iris.csv
- **Description**: [Id, SepalLengthCm,	SepalWidthCm,	PetalLengthCm,	PetalWidthCm,	Species]

**STEPS PERFOMERED**
### 1. Load the Dataset
Used `pandas.read_csv()` to load the dataset into a DataFrame.

### 2. Explore the Dataset
- `.shape` – to get number of rows and columns  
- `.columns` – to list all column names  
- `.head()` – to view the first 5 rows

### 3. Visualizations

#### Scatter Plot
- Shows relationship between two numerical features.

#### Histogram
- Displays distribution of a specific feature.

#### Box Plot
- Highlights the spread of values and potential outliers.
- 
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Data structure
print(df.shape)
print(df.columns)
print(df.head())

# Visualization
sns.scatterplot(x='ColumnX', y='ColumnY', data=df)
plt.title("Scatter Plot of ColumnX vs ColumnY")
plt.show()
