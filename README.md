# README — Mercer General Project 

## Objective
This project focuses on practicing data cleaning techniques in Python. 

## DAY 1
The main task for Day 1 is to clean the **Gender** column within an Emergency Department dataset at Mercer General Hospital.

The dataset originally contained inconsistent and non-standard gender entries (referred to as “dirty” data). These values were cleaned and transformed into a consistent numeric format that can be used for future analysis and modeling.

After cleaning, the **Gender** column is encoded as follows:

- **1 = Male patients**  
- **0 = Female patients**
- **-1 = unkown**

---

## Dataset/Input

**File used:** `EmergencyTriageDataset_Reduced_Dirty.csv`

## Output

**Cleaned dataset generated:** `EmergencyTriageDataset_Reduced_Clean.csv`


## DAY 2

The main task for Day 2 is to clean the **Fio2** column within an Emergency Department dataset at Mercer General Hospital.

Although the original dataset did not contain values outside the valid range (below 21% or above 100%), it included missing values (NaN). These missing entries were identified and imputed uding the mode to ensure the column was in a consistent and usable format.

This approach was selected because it preserves the most frequently occurring clinical value in the dataset without adding unnecessary variation into the distribution.

## Data Cleaning Steps (Fio2 Column)

- Checked for invalid or out-of-range values
- Identified missing values (NaN) in the **Fio2** column  
- Analyzed distribution to determine appropriate imputation method  
- Filled missing values using the mode value  
- Ensured consistency and readiness for later analysis


## Dataset/Input

**File used:** `EmergencyTriageDataset_Reduced_Dirty.csv`
