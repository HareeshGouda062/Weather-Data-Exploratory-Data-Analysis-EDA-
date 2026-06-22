Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a weather dataset using Python.
The objective is to clean the data, identify patterns, analyze weather-related variables, and uncover relationships between atmospheric conditions such as Ozone, Temperature, Solar Radiation, Wind Speed, and Weather Categories.

 Objectives
* Assess data quality and handle missing values.
* Detect and analyze outliers.
* Understand the distribution of weather variables.
* Explore relationships between environmental factors.
* Identify seasonal and temporal weather patterns.
* Generate insights through statistical and visual analysis.

 Tools & Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

Dataset Features
* Feature->Description
* Ozone->Ozone concentration level
* Solar->Solar radiation measurement
* Wind->Wind speed
* Temp->Temperature
* Weather->Weather condition category
* Month->Month of observation
* Day->Day of observation
* Year->Year of observation

 Data Cleaning & Preprocessing
* Loaded and inspected the dataset structure.
* Checked data types and missing values.
* Removed duplicate records.
* Filled missing values in the Ozone column using mean imputation.
* Renamed columns for better readability.
* Created a Date column from Year, Month, and Day fields.
* Removed unnecessary columns.

Exploratory Data Analysis
1. Univariate Analysis
   * Performed analysis on individual variables to understand their distributions.

Outlier Detection
   * Identified outliers in Ozone concentration using box plots.

Categorical Analysis
   * Analyzed frequency distribution of Weather conditions.
   * Examined monthly observation counts.
  
Numerical Analysis
*  Calculated variance and skewness of numerical features.
*  Visualized distributions using:
  *    Histograms
  *    KDE Plots
  *    Violin Plots
  *    Box Plot
    
2. Bivariate Analysis
  * Ozone vs Temperature
    * Explored the relationship between Ozone concentration and Temperature using scatter plots.
    * Investigated potential correlations between the two variables.

  * Weather vs Ozone
    * Compared Ozone distributions across different weather conditions using box plots.
    
  * Month vs Weather
    * Used cross-tabulation to analyze weather occurrence patterns across months.

3. Multivariate Analysis
    * Weather Impact Analysis
      * Visualized the relationship between Ozone and Temperature across weather conditions using color-coded scatter plots.

  * Pair Plot Analysis
    * Examined pairwise relationships among numerical weather variables.
    * Identified correlations, clusters, and variable interactions.

  Correlation Analysis
    * Generated a heatmap to analyze relationships between:
    * Ozone
    * Solar Radiation
    * Wind Speed
    * Temperature

4. Time-Series Analysis
  * Created line plots to track Ozone concentration over time.
  * Analyzed how weather conditions influence Ozone trends across dates.

5. Statistical Analysis
* Performed grouped statistical calculations to answer business-style questions:
* Average numerical measurements during sunny weather.
* Average temperature during cloudy weather in June.
* Maximum wind speed during sunny weather in July.
* Weather distribution across months.

Key Insights
* Ozone levels show varying relationships with temperature under different weather conditions.
* Weather patterns differ significantly across months.
* Numerical weather variables exhibit varying degrees of skewness and dispersion.
* Correlation analysis reveals relationships among atmospheric factors that influence air quality.
* Outlier detection highlights unusual environmental observations requiring further investigation.

Project Outcomes
* Improved understanding of weather data characteristics.
* Identified trends, anomalies, and relationships among environmental variables.
* Demonstrated end-to-end EDA workflow including data cleaning, visualization, statistical analysis, and insight generation.

 Visualizations Included
* Box Plots
* Histograms
* KDE Plots
* Violin Plots
* Scatter Plots
* Pair Plots
* Correlation Heatmaps
* Line Charts
* Bar Charts
* Cross-Tabulation Analysis
