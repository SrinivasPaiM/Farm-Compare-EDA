# Crop Production Trends Analysis

This project explores crop production trends over the years using a dataset of farm production records. The analysis focuses on identifying key trends, comparing the highest and lowest production crops, and understanding the variability and contributions of different countries.

## Notebook Overview

The notebook `farm.ipynb` is structured as a story-driven exploratory data analysis (EDA) with the following sections:

### 1. **Introduction**
   - Provides an overview of the analysis objectives.
   - Highlights the focus on the highest production crop (**Tame Hay**) and the lowest production crop (**Peas, Dry**).

### 2. **Loading and Inspecting the Dataset**
   - Loads the dataset and performs basic checks to understand its structure and contents.
   - Preprocessing steps include handling missing values, renaming columns, and removing anomalies (e.g., data for the year 1954).

### 3. **Number of Crops Over the Years**
   - Visualizes the number of crops recorded each year to identify trends and anomalies.

### 4. **Average Production by Crop Type**
   - Calculates and visualizes the average production for each crop type.
   - Identifies **Tame Hay** as the highest producer and **Peas, Dry** as the lowest producer.

### 5. **Yearly Trends for Tame Hay and Peas, Dry**
   - Analyzes and visualizes the yearly production trends for the highest and lowest producers.

### 6. **Country-Level Contributions**
   - Examines how different countries contribute to the production of **Tame Hay** and **Peas, Dry**.

### 7. **Correlation Between Production and Farm Value**
   - Explores the relationship between production and total farm value for all crops.

### 8. **Variability in Production**
   - Analyzes the variability in production for all crops to understand consistency.

## Dataset

The dataset contains the following key columns:
- `Year`: The year of production.
- `Country`: The country where the crop was produced.
- `Type of crop`: The type of crop produced.
- `Production (metric tonnes)`: The total production in metric tonnes.
- `Total farm value (dollars)`: The total monetary value of the farm production.

## Usage

1. Clone the repository or download the files.
2. Open the `farm.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to reproduce the analysis.

## Requirements

The following Python libraries are required to run the notebook:
- `pandas`
- `seaborn`
- `matplotlib`
- `numpy`

Install the dependencies using:
```bash
pip install pandas seaborn matplotlib numpy
```

## Insights

- **Tame Hay** consistently shows the highest production across years and countries.
- **Peas, Dry** has the lowest production and higher variability.
- There is a positive correlation between production and farm value, with **Tame Hay** contributing significantly to the overall farm value.

## Future Work

- Extend the analysis to include other crops with moderate production levels.
- Perform predictive modeling to forecast future crop production trends.
- Explore the impact of external factors (e.g., weather, policies) on crop production.

## License

This project is licensed under the MIT License.
