# Customer Personality Analysis - Data Wrangling Project 
This project demonstrates essential **Data Wrangling** techniques applied to the "Customer Personality Analysis" dataset using **Pandas** in a **Google Colab** environment.

## Project Objectives
The goal was to transform raw customer data into a clean, structured format ready for analysis by performing the following steps:
1. **Discovering:** Exploring the dataset structure, dimensions, and statistics.
2. **Cleaning:** Handling missing values and ensuring data consistency.
3. **Structuring:** Correcting data types and restructuring for better performance.
4. **Enriching:** Extracting initial insights through data grouping.
5. **Publishing:** Exporting the final processed dataset.

## Tech Stack
* **Python**
* **Pandas** (Data manipulation)
* **Google Colab** (Development Environment)

## Workflow

### 1. Data Discovery
- Used `df.info()`, `df.shape`, and `df.describe()` to understand the data distribution.
- Identified **24 missing values** in the `Income` column.

### 2. Data Cleaning
- **Missing Values:** Imputed missing values in the `Income` column using the **’Mean** to maintain statistical integrity.
- **Text Cleaning:** Standardized `Education` and `Marital_Status` columns using `str.lower()` and `str.strip()`.
- **Duplicates:** Verified that the dataset contains no redundant entries.

### 3. Data Type Correction
- Converted `Dt_Customer` to **datetime** format for time-based analysis.
- Converted flag columns (e.g, `AcceptedCmp`) and categorical data to the **category** type to optimize memory usage
 and no calculations should be performed on these columns because they represent states.
### 4. Data Structuring
- Performed **Grouping** (`groupby`) to calculate the average income based on education levels, providing immediate business insights.

## Project Outputs
- `Customer Personality Analysis data.csv`: The final cleaned and processed version of the dataset.

---
**Developed by:** [Mina azer]
