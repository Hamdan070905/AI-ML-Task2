# AI-ML-Task2

1. Import Libraries
   > Loads essential Python libraries: pandas, numpy, matplotlib, seaborn, and plotly for data handling and visualization.
2. Load Dataset
   > Reads a .csv file into a DataFrame using pandas.
3. Basic Data Understanding
   > Displays the first few rows of the dataset, checks data types, data shapes, and identifies missing values.
4. Summary Statistics
   > Provides numerical summaries like mean, median, standard deviation, and detailed descriptions for both numeric and categorical features.
5. Visualize Distributions
   > Generates histograms to check distribution/skewness.
   > Plots boxplots to identify outliers in numeric data.
6. Correlation & Relationships
   > Creates a correlation matrix heatmap to observe feature relationships.
   > Builds a pairplot to visualize feature pairings and their spread.
7. Pattern/Trend/Outlier Detection
   > Helps detect skewed distributions, trends, or unusual data behavior by interpreting visuals (no extra code here, just insights from previous charts).
8. Categorical vs Numeric Analysis
   > Plots bar charts for all categorical features.
   > Draws boxplots comparing a numeric column across different categories (e.g., Fare across Sex).
9. Interactive Visualizations (Optional)
   > Uses Plotly to generate interactive histograms and scatter plots for deeper exploration and presentation-friendly visuals.
10. Clean Final Dataset (One-liner)
   > Outputs a cleaned DataFrame by removing duplicates and missing data using:
              >cleaned_df = df.drop_duplicates().dropna()
