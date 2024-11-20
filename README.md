# Water Potability Analysis

This project focuses on analyzing the potability of water using statistical methods and machine learning techniques. The provided dataset contains various chemical properties of water samples, which are used to determine whether the water is safe for consumption.

## Project Files

1. **`FINALTERM_WATER_POTABILITY.R`**:
   - An R script that performs data cleaning, preprocessing, and analysis.
   - Key operations:
     - Handles missing data by replacing it with the median value of respective columns.
     - Converts the `Potability` column into a factor for categorical analysis.
     - Includes exploratory data analysis and potential modeling steps to classify water potability.

2. **`water_potability.csv`**:
   - The dataset used in this analysis, containing the following columns:
     - `ph`: pH level of the water.
     - `Hardness`: Amount of calcium and magnesium ions in the water.
     - `Solids`: Total dissolved solids (TDS) in ppm.
     - `Chloramines`: Amount of chloramines in ppm.
     - `Sulfate`: Amount of sulfate in ppm.
     - `Conductivity`: Electrical conductivity in µS/cm.
     - `Organic_carbon`: Organic carbon content in ppm.
     - `Trihalomethanes`: Concentration of trihalomethanes in µg/L.
     - `Turbidity`: Measure of clarity in NTU.
     - `Potability`: Target variable (0 = not potable, 1 = potable).

## Objectives

- Analyze the quality of water samples.
- Handle missing values effectively to prepare the dataset for analysis.
- Develop models or visualizations to classify and understand the factors affecting potability.

## Instructions

1. Install R and required packages (e.g., `ggplot2`, `caret`, etc.).
2. Load the dataset (`water_potability.csv`) using the `read.csv()` function.
3. Run the `FINALTERM_WATER_POTABILITY.R` script for analysis and results.

## Future Work

- Enhance the analysis with machine learning models for classification.
- Explore feature engineering to improve model performance.
- Provide a detailed visualization of potability trends and influencing factors.
