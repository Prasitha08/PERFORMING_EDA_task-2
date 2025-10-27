# PERFORMING_EDA_task-2
**1. Introduction**

Breast cancer is one of the most common cancers affecting women worldwide. Early diagnosis plays a vital role in improving survival rates and treatment outcomes.
This project focuses on performing Exploratory Data Analysis (EDA) on the Breast Cancer Wisconsin Dataset to understand patterns, trends, and correlations among various tumor features.

EDA helps to visualize relationships between attributes, identify key features distinguishing benign and malignant tumors, and detect anomalies or data quality issues before applying machine learning models.

The dataset contains 30 features (e.g., radius, texture, smoothness, symmetry) derived from a digitized image of a fine needle aspirate (FNA) of a breast mass. Each record is labeled as malignant (cancerous) or benign (non-cancerous).

**2. How It Works**

The project uses a structured EDA workflow to explore and visualize the dataset:

Step 1: Data Loading

Load the Breast Cancer dataset using sklearn.datasets.

Convert it into a Pandas DataFrame for easier manipulation.

Step 2: Data Inspection

Display dataset structure, shape, and data types.

Identify missing or inconsistent values.

Step 3: Descriptive Statistics

Generate summary statistics like mean, median, min, max, and standard deviation.

Provide an overview of feature distributions.

Step 4: Data Visualization

Use Seaborn and Matplotlib to plot histograms, boxplots, and correlation heatmaps.

Compare feature distributions between malignant and benign classes.

Step 5: Correlation Analysis

Identify highly correlated features using a heatmap.

Detect which features most strongly relate to diagnosis.

Step 6: Outlier Detection

Visualize feature ranges using boxplots to identify extreme or unusual values.

Step 7: Hypothesis Testing

Perform statistical tests (like t-test) to compare feature means between malignant and benign groups.

Determine which features show significant differences.

Step 8: Relationship Analysis

Use pairplots to visualize relationships between multiple features.





**google colab link**
https://colab.research.google.com/drive/1CpodnEXJyY23hlV9l4it72zANn1ZzzOF?usp=sharing
