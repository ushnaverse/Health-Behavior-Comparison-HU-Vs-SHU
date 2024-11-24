# Health & Behavior Data Merging: HU vs SHU

This repository contains the process and code for merging and validating datasets from **HU** and **SHU**, focused on health and behavior data. The goal was to clean, standardize, and merge the data for accurate analysis.

## Project Overview

- **Datasets Involved**: HU and SHU health & behavior data
- **Objective**: Consolidate both datasets into a clean, standardized format to enable reliable analysis.
- **Key Steps**:
  - Merged overlapping columns from HU and SHU.
  - Standardized column names, formats, and data types.
  - Reorganized and reformatted COVID-19 history data.
  - Handled missing, redundant, and outlier data.

## Dataset Details

- **Final Merged Dataset**: 245 rows, 154 columns
- Includes key fields such as height, weight, and COVID history.
- Outliers in height and weight identified for further cleaning.

## Steps Taken

1. **Merging HU and SHU Data**:
   - Imported both datasets and merged common columns.
   - Removed rows with missing values (NaN).
  
2. **Column Standardization**:
   - Cleaned overlapping columns, ensuring consistent naming and data formats.
  
3. **COVID-19 History Formatting**:
   - Reformatted COVID-related fields in SHU to match HU’s structure.

4. **Outlier Handling**:
   - Flagged potential outliers (e.g., unusual height/weight entries) for future review.

## Challenges

- **Inconsistent Column Names**: Standardized column names across datasets.
- **Missing/Redundant Data**: Removed irrelevant or sparsely populated columns.
- **Data Alignment**: Manually verified a subset of merged rows for accuracy.

## Next Steps

- Further clean and address flagged outliers.
- Begin data analysis using the cleaned dataset.

---

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Health-Behavior-Data-Merging.git

P.S.: the project is in progress....
