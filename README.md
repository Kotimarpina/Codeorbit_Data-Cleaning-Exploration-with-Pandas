# Data Cleaning & Exploration with Pandas

## Project Overview

This project focuses on data cleaning and initial exploration of the Titanic dataset using Python and Pandas. The objective is to identify data quality issues, handle missing values, check duplicate records, inspect data types, and generate basic statistical summaries.

This project was completed as part of the **Data Science Internship at CodeOrbit Tech**.

## Objectives

- Load and inspect a CSV dataset using Pandas.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Examine column data types.
- Calculate descriptive statistics such as mean and median.
- Explore categorical variables using value counts.
- Export the cleaned dataset for further analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset

The project uses the Titanic passenger dataset, containing information such as passenger age, gender, ticket class, fare, cabin, embarkation point, and survival status.

**Original dataset:** `Titanic-Dataset.csv`

## Data Cleaning Process

The following operations were performed:

1. Loaded the dataset using `pd.read_csv()`.
2. Inspected records, dimensions, column information, and descriptive statistics.
3. Identified missing values across columns.
4. Replaced missing Age values using the median.
5. Replaced missing Embarked values using the mode.
6. Replaced missing Cabin values with `Unknown`.
7. Checked duplicate records and applied duplicate removal.
8. Inspected column data types.
9. Calculated mean, median, and categorical value counts.
10. Validated and exported the cleaned dataset.

## Project Structure

```text
CodeOrbit-Data-Cleaning-Pandas/
│
├── Dataset/
│   └── Titanic-Dataset.csv
│
├── Cleaned_Data/
│   └── Titanic_Cleaned.csv
│
├── Notebooks/
│   └── Task_1_Codeorbit_Data_Cleaning.ipynb
│
├── Reports/
│   └── CodeOrbit_Task_1_Data_Cleaning_Report.pdf
│
└── README.md
```

## Key Outcomes

- Identified missing values in Age, Cabin, and Embarked.
- Applied appropriate missing-value handling techniques.
- Verified duplicate records.
- Inspected numerical and categorical data types.
- Generated statistical summaries.
- Exported the cleaned Titanic dataset.

## How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the Task 1 notebook.
5. Execute the cells sequentially.

## Output

The cleaned dataset is available in the `Cleaned_Data` folder and can be used for further exploratory data analysis.

## Internship Details

**Organization:** CodeOrbit Tech  
**Program:** Data Science Internship  
**Task:** Data Cleaning & Exploration with Pandas  
**Dataset:** Titanic Dataset

---

*This project demonstrates practical data preparation and exploratory skills using Python.*
